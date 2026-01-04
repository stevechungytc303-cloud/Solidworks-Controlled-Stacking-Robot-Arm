# Solidworks-Controlled-Stacking-Robot-Arm
This project uses macros created with SolidWorks API to extract pick-up and drop-off coordinates from two SolidWorks assembly files: one showing the robot's starting environment and one showing the final stacked layout. After the extraction, a temporary PowerShell script is generated to send the coordinates to the computer port connected to the robot. With the coordinates, the robot starts picking up and placing objects to recreate the final stacked layout. (More info and Demo Video Below)

## Robot Info
![Robotic Arm](SolidworksControlledStackingRobotImage.png)
- **Gearboxes**: Three custom-designed structurally fused 1:20 cycloidal gearboxes that provide 15 Nm of torque and compact form factor
<div style="display: flex; gap: 10px;">
  <img src="./Screenshot%202026-01-04%20182313.png" width="300">
  <img src="./Screenshot%202026-01-04%20181729.png" width="300">
</div>

- **Payload Capacity**: Can lift and move objects up to 1.5kg within a 50cm radius using a vacuum suction mechanism for reliable pick-and-place operations

- **Kinematics**: Uses inverse kinematics to calculate joint angles for reaching target positions in coordinate system

**CAD Link**: (https://cad.onshape.com/documents/097e38ababde583614ff8f42/w/25279c4533738fe7fa96ac7e/e/bf08222572276364fd7f60fc?renderMode=0&uiState=695af839b7b30ead00e6e3a0)

## Demo Video

Watch the robot in action:  
[![Robot Demo](https://img.youtube.com/vi/8PGG2dZVc4I/0.jpg)](https://www.youtube.com/shorts/8PGG2dZVc4I)

