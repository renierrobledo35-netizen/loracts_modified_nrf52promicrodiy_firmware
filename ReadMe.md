# LoRaCTS Modified nRF52 ProMicro DIY Firmware

LoRaCTS (LoRa Communication and Tracking System) is a modified Meshtastic firmware project developed for LoRa-based mesh communication and GPS-integrated messaging. 
It is designed to support off-grid communication, emergency assistance, and location sharing without relying on cellular networks or internet connectivity for LoRa message transmission.

## Project Overview
This repository contains the modified firmware source code for the LoRaCTS project, based on the Meshtastic firmware.
The firmware is customized for the nRF52840 ProMicro DIY hardware platform using an SX1262 LoRa radio module.

## Hardware Platform
- Microcontroller: nRF52840
- LoRa Radio: SX1262
- Hardware: ProMicro DIY / fakeTec PCB
- GPS Module: u-blox NEO-6M
- Operating Frequency: 915 MHz (subject to applicable regional regulations)

## Project Objectives
- Enable off-grid communication through LoRa mesh networking.
- Support GPS-integrated messaging.
- Provide location information during emergency assistance requests.
- Explore firmware customization for the LoRaCTS hardware platform.

## Development Environment
- Visual Studio Code
- PlatformIO
- Git
- Meshtastic Firmware

## Repository Contents
- `src/` - Main firmware source code.
- `variants/` - Hardware-specific configurations and variants.
- `boards/` - Board definitions and configurations.
- `platformio.ini` - PlatformIO build configuration.

## Building the Firmware
1. Clone or download this repository.
2. Open the project using Visual Studio Code with PlatformIO installed.
3. Select the appropriate nRF52 ProMicro DIY build environment.
4. Compile the firmware.
5. Flash the resulting firmware to the supported hardware.

## Project Information
Project Name: LoRa Communication and Tracking System (LoRaCTS)

Institution: Polytechnic University of the Philippines

Program: Diploma in Electronics Engineering Technology

## Acknowledgment
This project is based on the open-source Meshtastic firmware. Original project: https://github.com/meshtastic/firmware

LoRaCTS modifications are intended for academic research, development, and testing purposes.


********** UF2 File is the firmware **********
