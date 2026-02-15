# Smart Cooler Automation System

An automatic temperature-controlled cooling system developed using Arduino.

This project monitors ambient temperature and controls a cooling mechanism (fan or motor) automatically based on predefined thresholds.

---

## Overview

The Smart Cooler system is designed to optimize cooling efficiency using sensor-based automation.

The system:

- Reads temperature data from a sensor
- Activates cooling system when temperature exceeds threshold
- Deactivates cooling when temperature drops
- Operates autonomously

Suitable for:

- Small cooling systems
- Industrial ventilation
- Temperature-regulated environments
- Educational embedded projects

---

## Features

- Automatic temperature monitoring
- Threshold-based activation
- PWM-based speed control (if implemented)
- Relay or transistor driver control
- Proteus simulation included
- HEX file available

---

## Hardware Components

- Arduino Uno
- Temperature Sensor (LM35 / DHT compatible)
- Fan or Cooling Motor
- Relay Module or MOSFET driver
- Power Supply

---

## Software

- Arduino IDE (.ino file included)
- Proteus simulation project
- Compiled HEX file

---

## Project Structure

```
Smart-Cooler/
/
/// firmware/
/ /// smart_cooler.ino
/
/// simulation/
/ /// proteus-project.pdsprj
/
/// images/
    /// simulation.png
```

---

## Working Principle

1. Temperature sensor continuously monitors environment.
2. Arduino processes sensor data.
3. If temperature exceeds set threshold:
   - Cooling system activates.
4. When temperature drops below limit:
   - System turns off cooling.
5. Loop repeats for continuous regulation.

---

## Future Improvements

- LCD temperature display
- IoT monitoring via WiFi
- Adjustable threshold using keypad
- Energy optimization algorithm
- PCB design for compact deployment

---

## License

This project is licensed under the MIT License.

---

## Author

Developed by Soheil Ahmadi  
Embedded automation project.
