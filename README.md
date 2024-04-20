# Smart-health-monitoring-system-for-Covid-19-Patients
## Overview 
This IoT health monitoring system, implemented on Arduino UNO, collects real-time data for doctors, utilizing high-speed internet and cloud storage for efficient monitoring. It aids in early identification and treatment of COVID-19 patients by monitoring vital signs and symptoms, with added alert features for emergencies, ensuring early diagnosis and prevention of critical conditions.

## Modules Used
- **Display Module:** Utilizes the Liquid Crystal library to control LCD displays compatible with Arduino UNO. It involves manipulation of several interface pins, including register select (RS), Read/Write (R/W), Enable, and 8 data pins (D0 - D7), allowing for data writing and reading.
- **Button:** Incorporates pushbuttons or switches to connect points in a circuit. When pressed, the button makes a connection between its two legs, resulting in a HIGH input. This module can be configured with a pull-up resistor to read a LOW input when the button is pressed.
- **Buzzer:** The Arduino Buzzer produces sound when an electric current passes through it. Connected directly to the Arduino, it generates different tones by varying the frequency of electric pulses. This module can be controlled within the loop() routine.
- **Pulse Acquisition Module:** A miniature acquisition module for pulse-related measurements, maintaining low power for extended battery life. It provides wireless outputs in rpm, Hz, and time, while also counting pulses and measuring the period between them. Operating on license-free 2.4GHz, it ensures data integrity and security while minimizing local radio interference.
- **Body Temperature Acquisition Module:** Monitors the body temperature of patients, particularly crucial during pandemics and various diseases. Utilizing a temperature sensory module, it plays a vital role in diagnosing illnesses.
- **Heart Rate Acquisition Module:** Measures heart rate variability (HRV), an essential physiological variable for estimating cardiac autonomic function.
- **ESP8266 Wi-Fi Module:** A self-contained SOC with an integrated TCP/IP protocol stack, providing access to WiFi networks for any microcontroller. Capable of hosting applications or offloading WiFi networking functions from another processor, it offers powerful on-board processing and storage, facilitating seamless integration with sensors and other devices via GPIOs. This module enables effortless connectivity to Arduino UNO for the project's implementation.

## System Architecture 
![Sai Maansi Resume](https://github.com/saimaansi13/Smart-health-monitoring-system-for-Covid-19-Patients-/assets/125540201/74723325-a753-4b8a-861d-eacd954027b9)

## Hardware Requirements

  ![Your paragraph text (1)](https://github.com/saimaansi13/Smart-health-monitoring-system-for-Covid-19-Patients-/assets/125540201/b7d66ad9-1a66-4a0f-891f-e32464f2c959)
![Your paragraph text](https://github.com/saimaansi13/Smart-health-monitoring-system-for-Covid-19-Patients-/assets/125540201/290f28d6-1c65-4505-b62e-7b51474e4046)

## Software Requirement
### ThingSpeak
ThingSpeak, an IoT cloud platform, facilitates the transmission of sensor data, visualization, and analysis using tools such as MATLAB.

