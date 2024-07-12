# ESP32-Simulator-with-PIR-sensor
https://wokwi.com/projects/403219759500260353

What is a PIR Sensor?

A PIR (Passive Infrared) sensor is an electronic sensor that measures infrared (IR) light radiating from objects in its field of view. PIR sensors are commonly used in motion detection devices. They are called "passive" because they do not emit any energy themselves but detect the energy emitted by other objects.


PIR sensors work based on detecting the infrared radiation emitted by warm objects, such as humans and animals. When a warm object moves within the sensor's range, it causes a change in the amount of infrared radiation detected by the sensor, triggering a signal.

What we need :

ESP32 microcontroller

PIR sensor 

LED

Breadboard and jumper wires

Reads the value from the PIR sensor.
If the PIR sensor detects motion (pirValue == HIGH), it turns on the LED and prints a message to the serial monitor.
If no motion is detected, it turns off the LED.
