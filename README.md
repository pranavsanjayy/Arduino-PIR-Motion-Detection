# Embedded Systems & IoT – Task 2

## PIR Motion Sensor Interfacing with Arduino UNO

### Objective

The objective of this task is to interface a PIR (Passive Infrared) motion sensor with an Arduino UNO and control an LED based on detected motion.

### Components Used

- Arduino UNO
- PIR Motion Sensor
- LED
- 220Ω Resistor
- Jumper Wires
- Tinkercad Circuits

### Circuit Connections

| Component | Arduino UNO |
|---|---|
| PIR Power | 5V |
| PIR Signal | D2 |
| PIR Ground | GND |
| LED | D13 through 220Ω resistor |
| LED Ground | GND |

### Working

The PIR sensor detects motion and sends a digital signal to the Arduino through digital pin D2.

When motion is detected, the sensor output becomes HIGH. The Arduino then turns ON the LED connected to digital pin D13.

When no motion is detected, the LED is turned OFF.

The motion status is also displayed through the Serial Monitor.

### Code

The Arduino continuously reads the PIR sensor and controls the LED according to the sensor output.

### Result

The PIR motion sensor was successfully interfaced with the Arduino UNO. The LED turns ON when motion is detected and turns OFF when there is no motion.

### Simulation

The circuit was implemented and tested using Tinkercad Circuits.