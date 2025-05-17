# Smart-Home-Surveillance-System
 This project was completed as part of the Student Membership Program organized by IEEE NITK. Under the guidance of my mentors, I successfully designed and implemented both the hardware and software part of the system.

Introduction:
 This project implements a basic smart home surveillance system that activates lights and a buzzer in response to motion detection.A  kind of Anti theft system. This uses standard electronic components including a PIR sensor, BJT transistor, and a 555 timer configured in monostable mode.

 
Overview:
 The system functions as a motion-based alert mechanism for home security. It detects motion using a PIR sensor, amplifies the signal using a BJT in a voltage divider configuration, and then uses a 555 timer to generate a pulse output. This pulse drives the activation of lights and a buzzer.


Methodology:
A PIR sensor continuously monitors for motion.
When motion is detected, the PIR sensor outputs a weak signal.
This signal is amplified using an NPN BJT in a voltage divider configuration.
The amplified signal triggers a 555 timer operating in monostable mode.
The timer generates a high pulse for a specific duration, during which the buzzer and lights are turned on.

The output pulse duration for the 555 timer is determined by the equation:
T = 1.1 * R * C
where R and C are the timing resistor and capacitor values respectively

The file also includes simulations for individual setups to ensure proper understanding of the system.


Components Used:
PIR motion sensor
NPN BJT
555 timer IC
Resistors and capacitors
LEDs or AC lights
Buzzer
Power supply 
Breadboard and wires.

Feel free to simulate once on your own.
