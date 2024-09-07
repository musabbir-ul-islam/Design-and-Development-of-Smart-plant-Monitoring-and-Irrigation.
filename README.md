# Design-and-Development-of-Smart-plant-Monitoring-and-Irrigation.
A IoT based device that will provide with smart irrigation system and plant monitoring

This project is an IoT-based system designed to monitor plant health and automate irrigation. The system measures environmental parameters such as soil moisture, temperature, and humidity and automatically controls the water supply to ensure optimal growth conditions for plants.

## Features

- **Soil Moisture Monitoring**: Measures soil moisture levels to determine when irrigation is needed.
- **Temperature & Humidity Monitoring**: Tracks environmental conditions to ensure they are suitable for plant growth.
- **Automated Irrigation**: Controls water supply based on soil moisture readings to prevent over- or under-watering.
- **Remote Monitoring**: Provides real-time data on environmental conditions via a web or mobile interface.
- **Alert Notifications**: Sends notifications when plants need attention, such as low moisture levels.

## Components Used

- **Microcontroller**: ESP8266/Arduino or any IoT-compatible microcontroller.
- **Soil Moisture Sensor**: Monitors the soil's water content.
- **DHT11/DHT22 Sensor**: Measures temperature and humidity levels.
- **Water Pump**: Automatically waters the plants when needed.
- **Relay Module**: Controls the water pump.
- **Power Supply**: A 9V or 12V battery to power the system.

## How It Works

1. **Initialization**: The microcontroller gathers data from the sensors and initializes the system.
2. **Soil Moisture Detection**: If the soil moisture falls below a certain threshold, the system triggers the water pump.
3. **Environmental Monitoring**: The DHT sensor monitors temperature and humidity to ensure optimal growth conditions.
4. **Automated Irrigation**: The water pump irrigates the plants automatically when soil moisture is low.
5. **Remote Data Access**: Sensor data is sent to the cloud for real-time monitoring via a web or mobile app.
6. **Alerts**: The system sends notifications when critical thresholds are reached (e.g., soil moisture too low or high temperatures).

## Circuit Diagram

![Circuit Diagram](https://github.com/user-attachments/assets/efdc9ef7-17d2-40ae-b554-0d71128fa374)


## Software & Libraries

- **Arduino IDE** or any compatible platform for microcontroller programming.
- **Libraries**:
  - DHT (for temperature and humidity sensing)
  - Adafruit Sensor (for interfacing with sensors)
  - WiFi (for ESP32 or other Wi-Fi modules)
  - Thingspeak/Blynk or any IoT platform for cloud integration and monitoring

## Installation & Setup

1. Code: https://github.com/musabbir-ul-islam/Design-and-Development-of-Smart-plant-Monitoring-and-Irrigation.
2. Open the project in the Arduino IDE or any other compatible platform.
3. Install the required libraries using the Arduino Library Manager.
4. Upload the code to your microcontroller.
5. Assemble the components as per the circuit diagram.
6. Configure the Wi-Fi module with your network credentials and set up your IoT platform (e.g., Blynk or Thingspeak) to view data remotely.

## Usage

- Once powered on, the system continuously monitors soil moisture, temperature, and humidity.
- If the soil moisture drops below the threshold, the water pump is activated to irrigate the plants.
- Data can be accessed remotely through the connected IoT platform.
- Set up alert notifications for critical conditions, such as low soil moisture or high temperatures.

## Future Enhancements

- Add more sensors for light intensity and pH levels.
- Integrate with a mobile app for enhanced control and customization.
- Implement a power-saving mode to increase the system’s energy efficiency.

## License

This project is open-source and available under the MIT License.

