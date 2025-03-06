# Smart Home Automation using NodeMCU and Relay Module with Sinric Pro

## Overview
This project demonstrates an efficient and cost-effective **Smart Home Automation** system using **NodeMCU (ESP8266)**, **Relay Module**, and **Sinric Pro**. It allows users to remotely control appliances via a mobile app or voice assistant.

## Features
- Seamless device control with NodeMCU and Relay Module.
- Cloud-based communication using Sinric Pro.
- Voice assistant and mobile app support.
- Cost-effective home automation solution.
- Remote monitoring and control of home appliances.
- Potential for future AI and IoT integration.

## System Architecture (Workflow)
1. **User action**: Sends a command via a mobile app or voice assistant.
2. **Cloud request**: The request is sent to Sinric Pro, which authenticates and processes it.
3. **NodeMCU execution**: The command is relayed to NodeMCU via WiFi.
4. **Appliance control**: The Relay Module switches the connected appliance on/off based on the command.

## Hardware Components
- **NodeMCU (ESP8266)** – Microcontroller with WiFi capability.
- **4-Channel Relay Module** – Controls home appliances.
- **Power Supply** – To power the NodeMCU and relay module.

## Software & Platforms
- **Arduino IDE** – Used for programming the NodeMCU.
- **Sinric Pro** – Cloud platform for IoT-based device control.
- **WiFi Network** – Required for cloud connectivity.

## Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/nik-krish/Smart-Home-Automation.git
   ```
2. **Install required libraries** in Arduino IDE:
   - `ESP8266WiFi.h`
   - `ArduinoJson.h`
   - `SinricPro.h`
3. **Configure Sinric Pro:**
   - Create an account on [Sinric Pro](https://sinric.pro/).
   - Generate an API key and device ID.
   - Update `config.h` with these credentials.
4. **Upload the Code** to NodeMCU:
   - Connect NodeMCU to the PC via USB.
   - Select the correct **board (NodeMCU 1.0)** and **port** in Arduino IDE.
   - Upload the sketch.

## Usage
- Open the **Sinric Pro app** on your smartphone.
- Add the configured devices.
- Use voice commands (via Alexa/Google Assistant) or the app to control appliances.

## Future Enhancements
- **Energy Monitoring**: Track and optimize power consumption.
- **Security Enhancements**: Implement biometric authentication and encrypted communication.
- **Machine Learning Integration**: Automate devices based on user behavior.

## License
This project is open-source and available under the MIT License.
