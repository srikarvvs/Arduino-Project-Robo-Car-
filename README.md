# Arduino-Project-Robo-Car-

# Description : 
For this firstly the application program is developed or a readymade
program is made available to run on the PC or the mobile phone. This
application program send the commands in form of ASCII characters
which are received by HC-05 Bluetooth module and passed to
microcontroller through UART port of microcontroller.


The microcontroller is programmed to take desired actions according to
the command (ASCII character) received to move forward, reverse or to
take a turn.


The microcontroller sends logic 1 or 0 at the specified pin to control
motors of robot which are attached using motor driver IC (L293D).

# Hardware components required and their purpose:

1. Arduino board
2. PC or Mobile phone with customizable Bluetooth module
3. HC-05 Bluetooth module
4. DC motor
5. Motor driver IC (L293D)
6. Wheels
7. Power adopter

 # Arduino board: 
 
This is the brain of this robot in which the
program is loaded to do the required functioning and is interfaced
with Bluetooth module and the motor driver to make the system work
as required.


# HC-05 Bluetooth Module: 

This module is capable of communicating
with PC, mobile phone or any other Bluetooth enabled device. It is
interfaced with the microcontroller over the
serial UART port of micro-controller.


# PC or Mobile phone with customizable Bluetooth module: 

This works
as the remote control for the robot. It has an application program
running on it which enables us to send appropriate command over its
Bluetooth module to control the robot.

# DC Motor: 

This motor is controlled with DC voltages and can move
in forward and backward direction according to the polarity of the
voltage applied.

# Motor driver IC (L293D): 

Microcontrollers can’t supply the
current required by DC motor to run. So, to fulfill this requirement
these motor driver ICs are used.
DC motors with Driver IC

# Power adopter:

This is used to give appropriate dc power supply to
microcontroller, driver IC sensors and the other passive components
of the robot.

# Wheels: 

In it three wheels are employed, two at rear end and one at
front end. Rear wheels are attached with the motors and also control
the steering of robot. Front wheel is the loose steered wheel which
moves in the direction of the pressure applied to it.


# Circuit Diagram : 

![Diagram 1](https://user-images.githubusercontent.com/44844695/97115308-1bed6d00-171c-11eb-9006-89d95ed57764.jpeg)

![Diagram 2](https://user-images.githubusercontent.com/44844695/97115310-2576d500-171c-11eb-88c7-9e3b19deb1fa.jpeg)

![Diagram 3](https://user-images.githubusercontent.com/44844695/97115311-26a80200-171c-11eb-8caa-7fa88c2e16b5.jpeg)

![Diagram 4](https://user-images.githubusercontent.com/44844695/97115312-27d92f00-171c-11eb-99c0-302b5978e3f5.jpeg)

![Diagram 5](https://user-images.githubusercontent.com/44844695/97115315-29a2f280-171c-11eb-9f7c-b004e15119f8.jpeg)
