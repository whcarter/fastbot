# fastbot
This program will use the Meltybrain programming technique to drive a Vex V5 robot while continuously spinning at high speeds. The program will have both a tank drive control mode and a Meltybrain control mode. 

## How it works
The Meltybrain control works by toggling the motors on and off rapidly based on inertial sensor input. The program determines an intended direction of travel from the joysticks on the controller and only runs each motor while the inertial sensor reports that the wheel is facing towards the intended direction of travel. 
