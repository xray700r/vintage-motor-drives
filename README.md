# vintage-motor-drives
Schematics that are old but work very well in the 21st century with Arduino and DIY stuff
 
Schematic nr. 1:  H bridge for DC motor control with relays

H bridge for DC motor control with relays is very useful when the cheap variants modules based on  L298P and L298N don't complete your needs for driving motors.
Relays are old components and do not have high switching speed but still for basic control they do their job well.

Schematic nr. 2: PWM signal variation switched with relays

In case PWM control of motors is needed this can be done through dhe switching of a PWM power signal instead of the DC voltage.
This simple variation yet needs a really powerful MOS-FET which must be capable of managing at least Ids=100A and Vgs=60V.
