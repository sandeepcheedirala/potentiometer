# Potentiometer Interfacing with Arduino Uno 🎛️

## Overview

This project demonstrates how to interface a **Potentiometer** with an **Arduino Uno** to read analog input values. The Arduino continuously reads the voltage from the potentiometer using its built-in Analog-to-Digital Converter (ADC) and processes the value for monitoring and control applications.

This project helps in learning:

* Arduino programming
* Analog input reading
* Analog-to-Digital Conversion (ADC)
* Sensor interfacing
* Embedded systems fundamentals

## Features

* Real-time analog value reading
* Smooth input control using a potentiometer
* Easy hardware setup
* Beginner-friendly Arduino project
* Suitable for learning ADC concepts

## Components Used

* Arduino Uno
* 10kΩ Potentiometer
* Jumper Wires
* USB Cable

## Circuit Connections

Connect the potentiometer to the Arduino Uno as follows:

* Left Pin → 5V
* Middle Pin (Wiper) → A0
* Right Pin → GND

The Arduino reads the voltage from the middle pin through analog pin A0.

## Live Simulation

You can view and test the live simulation of this project using the link below:

🔗 **Simulation Link:**https://wokwi.com/projects/468987722147864577

## Working Principle

The potentiometer acts as a variable resistor. As the knob is rotated, the output voltage changes.

The Arduino Uno:

1. Reads the analog voltage from the potentiometer.
2. Converts the analog voltage into a digital value using its built-in ADC.
3. Processes the value and displays it through the Serial Monitor or uses it to control other devices.

The analog reading typically ranges from **0 to 1023**, representing voltages from **0V to 5V**.

## How to Run

1. Clone this repository.
2. Open the project in Arduino IDE.
3. Connect the potentiometer according to the circuit diagram.
4. Upload the program to the Arduino Uno.
5. Open the Serial Monitor to observe the analog values.
6. Rotate the potentiometer knob and monitor the changing readings.
7. Run the live simulation or test the project on actual hardware.

## Applications

* Analog input measurement
* Brightness control
* Motor speed control
* Volume control
* Sensor calibration
* Embedded systems learning

## Future Improvements

* Control LED brightness using PWM
* Control servo motor position
* Display analog values on an I2C LCD
* Send sensor data to IoT platforms
* Add graphical visualization of sensor readings

## Author

Developed by **[CHEEDIRALA SANDEEP]**
