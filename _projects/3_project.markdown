---
layout: page
title:<h3> ROV Robot </h3>
description: 
img: /assets/img/rov_8.JPG
importance: 4
category: .
---

About
Remotely operated underwater vehicle robot which we developed in IRSE robotic team.
In our robot team, I was a project manager and head designer, my duties included project managing & designing essential sections of the robot such as propeller of thruster also performing some little works in control and electronics.

It will be described in more detail below:

The main body was developed with a waterproof feature because of the existence of the mainboard & camera by ORING and compressing air at least 5 bars.





<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_1.JPG' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_2.JPG' | relative_url }}" alt="" title="example image"/>
    </div>
     <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_3.JPG' | relative_url }}" alt="" title="example image"/>
    </div> 
</div>

One of the greatest of challenges in the mechanic of the robot was related to propeller designing:

Before designing the propeller, we had to calculate the drag of the robot so first of all, we design the main body and thrusters then by simulation of the robot in ANSYS fluent, we could get the drag coefficient & force.
By gaining drag force we could choose motors & perceiving what will be propeller requirements to design an accurate propeller furthermore some sample propellers were designed by PROP CAD & Solid Works then simulated by ANSYS fluent.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_4.JPG' | relative_url }}" alt="" title="example image"/>
    </div>
<div class="caption">
    Caption photos easily
</div> 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_5.JPG' | relative_url }}" alt="" title="example image"/>
    </div>
<div class="caption">
    Caption photos easily
</div> 

Also, I studied something about the control and linearization of kinematic equations and with the cooperation of my colleague, equations were derived. 

The mainboard of the robot is composed of network IC, RJ45, SD card connector, micro USB connector, 3.3V regulator for STM 32 microcontroller, IMU pin header, mini pc (ODROID for image processing under water), and so on.
I just spent a little time on electronics.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_6.JPG' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_7.JPG' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

Because of some problems in our team we couldn’t complete manufacturing.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/rov_8.JPG' | relative_url }}" alt="" title="example image"/>
    </div>
<div class="caption">
    Render of ROV robot
</div> 
