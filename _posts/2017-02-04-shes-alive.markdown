---
layout:     post
title:      "Motor: Spinning 👏"
date:       2017-02-04 12:00:00
author:     "Darshak Patel"
---

<h4>TL;DR: Speed control of the motor via the system’s microcontroller is complete.</h4>

---

<h3>Speed Control for Brushless DC Motor</h3>
<p>The VESC (Vedder Electronic Speed Controller) has been successfully interfaced with an Arduino Mega using commands over serial communication. The Arduino Mega can now tell the speed controller to make the motor spin at a certain speed and retrieve important parameters for monitoring such as current drawn by the motor, current drawn from the battery, input voltage, and rpm. This functionality will be useful for when the remote controller or phone controller tell the Arduino what to do. The speed controller uses a traditional PID controller to control the speed of the brushless DC motor. The motor is calibrated to work with the speed controller through an auto-detection process where the motor is sensed by the speed controller and the resulting parameters are used in the setup of the speed controller.</p>

---
---

<p>That's all for this week! I'll leave you with my favourite video/gif/picture of the week at the end of each blog post as a thank you for reading the blogposts 😄</p>

<p>Americans, explain yourself!</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/r5nt9ZDOiSc" frameborder="0" allowfullscreen></iframe>