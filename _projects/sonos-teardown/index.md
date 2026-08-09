---
layout: post
title: Capstone Senior Design Project
description: Unmanned Aerial Vehicle technology has matured rapidly over the past decade, opening the door to applications that extend well beyond traditional military and commercial use cases. One area that stands to benefit significantly is environmental management, where the ability to access remote terrain, cover large areas efficiently, and operate without risk to a human crew addresses challenges that conventional methods struggle to meet. The United States Forest Service faces two such challenges, the need to accelerate reforestation in burn-affected and degraded areas and the need to maintain reliable radio communication infrastructure in disaster-impacted regions where terrain and destruction limit ground-based options. My roles for the year long project were the control and stability lead and the manufacturing lead for STAR.    
skills: 
  - SolidWorks
  - Fusion 360 CAM
  - MATLAB
  - Athena Vortex Lattice (AVL)
  - CNC Machining
  - Soldering

main-image: /10ftRenderReal_Beauty.png
---
# STAR:
{% include image-gallery.html images="BETTER FINAL 10ft Render_Beauty.png" height="400" %}

## Stability Analysis
I utilized the Athena Vortex Lattice (AVL) software was used to determine the stability of the UAV; where its dimensions, weight, CG, and the potential flight conditions the UAV would face were inputted into. From here, various tests were conducted such as differing sideslip angles, angles of attack, and bank angles. The results were examined and I suggested different redesigns to make the UAV more stable. One such major modification that I suggested and was implemented was the addition of 5 degrees of dihedral to the wings, which greatly helped the spiral stability of our UAV.  

### AVL Setup Files:
{% include image-gallery.html images="AVL Setup.png" height="400"  %}
Above is the setup file for the 10 foot wing configuration. It contains the wing span, chord length, airfoil shape and when adding dihedral the height of various points along the wing utilizing the Z value.

{% include image-gallery.html images="Mass File Example.png" height="400" %}
Above is the mass file for the 10 foot wing configuration. After the UAV had been fully built I went and measured the weight of all the components and inputted them into the AVL mass file. Simultaneously I utilized SolidWorks to ensure there was not much weight difference and used the CG location based from the nose of the UAV and the moment of inertia of each part and inputted those as well. 

### 6 Foot and 10 Foot Wing Configurations:
{% include image-gallery.html images="AVL 6ft VV&T.png, AVL VV&T.png"  %}
Here is the UAV modeled in AVL in its 6 foot and 10 foot wing configurations.


### Stability Results:
{% include image-gallery.html images="6ft AVL Results.png, 10ft AVL Results.png" height="400" %}
6ft and 10ft AVL Stability Results respectfully.

## Part Designs:
