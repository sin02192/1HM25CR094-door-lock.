## Testing

1. Start the ESP32 simulation in Wokwi.
2. Connect ESP32 to Wi-Fi.
3. Connect to the HiveMQ MQTT broker.
4. Subscribe to the project MQTT topic.
5. Send the LOCK command.
6. Send the UNLOCK command.
7. Verify the commands in the Serial Monitor.

## Result

The Smart Door Lock receives remote LOCK and UNLOCK commands through MQTT.
 ## MQTT Communication

The project uses the MQTT protocol for communication.

### MQTT Broker
HiveMQ Public Broker

### MQTT Topic
pesnext/w5/1HM25CR094/cmd

### Supported Commands
- LOCK
- UNLOCK
- ## Project Features
- Remote door locking using MQTT.
- Remote door unlocking using MQTT.
- ESP32-based control system.
- Wi-Fi connectivity.
- # ESP32 Smart Door Lock using MQTT

## Project Description
This project implements a Smart Door Lock using ESP32 and MQTT communication.

## Technologies Used
- ESP32
- MQTT Protocol
- HiveMQ Broker
- Google Colab
- Wokwi Simulator

## Working
1. ESP32 connects to Wi-Fi.
2. HiveMQ handles MQTT communication.
3. Google Colab publishes LOCK and UNLOCK commands.
4. ESP32 receives the commands and controls the door lock.

## MQTT Topic
`pesnext/w5/1HM25CR094/cmd`

## Commands
- LOCK
- UNLOCK

## Developed for
Internal Lab Evaluation
