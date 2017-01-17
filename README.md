# README
## RAS-J 12/01/2017

## Introduction
Here the design of a POF sensor is presented for the remote monitoring of a distillation column for use in undergraduate labs within Chemical Engineering.

## Hardware layout
The circuit is based around the LT1920 instrumentation amplifier which is used to amplify the signal from a photodiode with an incorporated trans-impedance amplifier.  

- Power input: this is supplied from a 12V supply connected to a 2.5mm jack on the front panel 
- LED power output: voltage for the LED's is connected to 2 banana plugs (red and black) on the front panel.
- Vsig output: this is the output signal and is connected by a BNC plug
- Vpd: the input from the photodiode.  This is at present connected via a 2.5mm audio jack but this can be replaced with a BNC connector

Resistors are used to set the levels for the offset voltage and the gain of the amplifier.  Switches are used to switch between variable resistors and fixed value resistors.  This is to enable the optimum level of both to be found and then set for future use.