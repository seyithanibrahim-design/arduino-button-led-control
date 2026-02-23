# arduino-button-led-control
A basic Arduino Uno project demonstrating digital input/output control of an LED via a push button with a pull-down resistor configuration.

Arduino Button-Controlled LED with Pull-Down Resistor:
This project demonstrates a fundamental digital input/output (I/O) application using an Arduino Uno. It focuses on controlling an LED state via a push button while implementing a pull-down resistor to ensure signal stability.

Project Overview:
In digital electronics, an unconnected input pin can pick up electrical noise, leading to "floating" states. This project utilizes a 10k Ohm pull-down resistor to tie the input pin to the ground (0V) when the button is not pressed, ensuring a reliable LOW reading.

Components List:
Microcontroller: Arduino Uno
Input: Push Button
Output: Red LED
Resistors: * 330 Ohm (Current limiting for LED)
10k Ohm (Pull-down for button)
Breadboard & Jumper Wires

Circuit Connection:
LED: Connected to digital pin 10 through a 330 Ohm resistor.
Button: Connected to digital pin 8.
Pull-Down Logic: One side of the button is connected to 5V; the other side is connected to pin 8 and also to GND through the 10k Ohm resistor.
