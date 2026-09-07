# Hackster.io

# OpenHealth Pod

OpenHealth Pod is a modular wearable health-monitoring project based on the Arduino UNO Q.

The plan is to combine:

- AD8232 ECG
- MAX30100 SpO2 / pulse sensor
- MPU6050 IMU
- DS18B20 temperature sensor
- Edge-AI processing
- Battery and power monitoring

## Current Status

The project is currently in the design stage.

So far:
- Initial system architecture is planned.
- Sensors have been selected.
- Initial BOM has been created.
- Sensor datasheets have been added.
- Initial enclosure design has been made in Autodesk Fusion.

## Planned Work

- Design the custom UNO Q shield PCB.
- Integrate the sensors onto the PCB.
- Develop STM32 firmware.
- Develop the Linux-side software.
- Train and deploy an ECG classification model.
- Add data logging and a local dashboard.
- Implement power management and watchdog monitoring.
- Finalize the wearable enclosure.
- Manufacture and assemble the prototype.
- Test the complete system with real sensor data.

The design and code will be updated in this repository as development progresses.

> This project is for engineering and educational purposes and is not intended to be a medical diagnostic device.
