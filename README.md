# Robotic-Arm-Simulation
Simulation and Tracking Position Control of a Two Degrees Freedom Arm Robot in Simulink
A two degree of freedom robot arm is described in the Figure below which consists primarily of  two links with the following specifications in OXY coordinates: 
* 𝐿1= 0.31 m is the length of the first link.  
* 𝐿2= 0.34 m is the length of the second link. 
* 𝑚1= 1.98 kg is the mass of the first link.  
* 𝑚2= 1.77 kg is the mass of the first link.
* 𝑚3= 0.447 kg is the mass of the arm robot end-point
* 𝜃1= the rotation angel of the first link.  
* 𝜃2= is the rotation angel of the second link. 

<p align="center">
<img src="https://user-images.githubusercontent.com/40741680/130276281-c0b79a86-b6c8-4659-ac74-d9132fd92d04.png" width="600" height="300">
</p>


## Arm Robot Control
* ### PID Controller
	The proportional-integral-derivative (PID) control has simple structure for its three gains. The control performances are acceptable in the most of industrial processes. Most robot manipulators found in industrial operations are controlled by PID algorithms independently at each joint. There are many control techniques used for controlling the robot arm. The most familiar control techniques are the PID control, adaptive control, optimal control and robust control. As the final goal is to design and manufacturing real robots, it's helpful doing the simulation before the investigations with real robots, to enhance the final real robot performance and behavior.
* ### Simulink Simluation

<p align="center">
<img src="https://user-images.githubusercontent.com/40741680/130277780-2fea0ddd-e791-4dbd-bab2-559cad0b9a8f.png" width="900" height="400">
</p>
<p align="center">
<b>Overview of the controlled system</b>
</p>
<br />


<p align="center">
<img src="https://user-images.githubusercontent.com/40741680/130278307-40ab1ac4-a3a1-4ae8-8592-ba6702be7e60.png" width="900" height="300">
</p>

<p align="center">
<b>The Simulated two DOF Robotic Arm</b>
</p>


<p align="center">
<img src="https://user-images.githubusercontent.com/40741680/130280263-850a995f-2b10-4fb8-a7ad-82df987d9774.jpg" width="900" height="500">
</p>

<p align="center">
<b>The Realization of the Arm Robot drawing a circle r=0.1m</b>
</p>

												
