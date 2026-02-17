# Averionics Typis 2.0 — Custom 3D Printer Firmware (Marlin-Based)

<img align="right" width=300 src="https://images.squarespace-cdn.com/content/v1/61ca29b5e4f1e935086a47af/5a491fad-54d8-4ff1-a08a-3e6ea7f35a25/Logo+-+Blue+No+Background.png?format=1500w" />

## Project Overview

**Author:** Nicole Mottier

**Repository Access:** Private — available to recruiters upon request

Designed and implemented custom firmware for the Averionics Typis 2.0 3D printer, based on the open-source Marlin firmware. This project involved adapting a large embedded C/C++ codebase to custom hardware, enabling advanced configuration, improved reliability, and optimized performance.

The firmware replaces stock printer software and serves as the primary control system for motion, thermal regulation, safety monitoring, and user interaction.

Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/) and [Averionics Firmware Update](https://www.averionics.com/download-update-firmware).

## Key Contributions

- Configured and customized Marlin firmware for proprietary hardware

- Integrated motion control parameters for stepper motors and kinematics

- Implemented thermal management tuning for hotend and heated bed

- Enabled hardware features including sensors, limit switches, and safety controls

- Optimized firmware settings for print quality and reliability

- Diagnosed and resolved low-level hardware communication issues

- Built and deployed firmware using PlatformIO toolchain

- Tested on physical hardware with iterative debugging

## Building Marlin

**Programming & Development**

- Embedded C/C++
 
- Working within a large open-source codebase
 
- Firmware configuration and compilation
 
- Debugging hardware-software interactions
 
- Version control with Git

**Systems & Hardware Integration**

- Microcontroller-based systems
 
- Real-time control logic
 
- Sensor integration
 
- Stepper motor control
 
- Thermal regulation systems

**Tools & Technologies**

- PlatformIO
 
- Git / GitHub
 
- Marlin Firmware
 
- 3D printer electronics (controller boards, drivers, thermistors)

## Build Instructions

**Requirements**

- PlatformIO
 
- Compatible microcontroller board
 
- Averionics Typis 2.0 hardware configuration

**Build Steps**

 1. Install PlatformIO
 
 2. Clone repository
 
 3. Open project in PlatformIO environment
 
 4. Compile firmware
 
 5. Flash to printer controller board

Detailed Marlin documentation is available via [Marlin Firmware](https://marlinfw.org/)

## Project Goals

- Provide stable, production-ready firmware for a custom 3D printer

- Improve performance over stock firmware

- Enable hardware-specific features not supported out-of-the-box

- Maintain compatibility with upstream Marlin development

## Testing & Validation

- Firmware was tested on physical hardware through:
   
- Print quality benchmarking
   
- Thermal stability checks
   
- Safety feature verification
   
- Long-duration print testing
   
- Failure recovery scenarios

## Licensing

This firmware is based on Marlin, which is distributed under the GPL license.
All derivative work complies with GPL requirements.

Averionics will provide compatible Marlin source code to end users upon request.

## Access Notice

This repository is private due to hardware-specific configuration and distribution considerations.

**Recruiters and hiring managers:**

Access can be granted upon request for evaluation purposes.

## Contact

Nicole Mottier

GitHub: [n861997](https://github.com/n861997)

Email: n861997@gmail.com

