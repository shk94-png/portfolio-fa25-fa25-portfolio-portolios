---
layout: project
title: Quadcopter Motor Analysis
description: Analsis of a quadcopter motor 
technologies: [Oscilloscope, High Speed Camera Analysis]
image: /assets/images/VoltageData.png
---

For this project I dissasembeled a quadcopter drone and used system synamics skills to model it. I started by filming its ramp up from zero to maximum thrust on a slow motion camera, and counted the frames per rotation to calculate RPM. In roughly 29 milliseconds our rotor accelerated to 17,000 RPM, which provided data to calculate a time constant. I then stripped the motor leads, hooked it up to an oscilloscope, and repeated the ramp up. Finally, I repeated this process with voltage and recalculated the time constant. By relating these two together, I can determine thrust as a function of voltage and time.