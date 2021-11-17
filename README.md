# MegaClock

The MegaClock project is an attempt to build a low cost, multiplexed display driver for HUGE 7 segment displays (i.e. 24 inch x 12 inch)built from 12v LED strips. current iteration uses the following: 

 1 - 74HC595 8 bit shift register
 11 - IRFZ44n MOSFETS
 1 - LM3805 Voltage Regulator
 + a few common caps and resistors.

This portion of the project is designed to be MCU agnostic, however, I've chosen to use a raspberry pi 0w as the MCU for the time being. The controller code can be found here: [http://www.github.com/whinchman/MegaClockPi]

 Project Milestones:
 



