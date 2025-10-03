# Setup Guide

## Using Sensor Examples

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-org/sensor-codebase.git
   ```

2. **Select Your Sensor**
   - Navigate to the `sensors/` directory.
   - Choose the sensor and platform folder (e.g. `sensors/SensorA/arduino/`).

3. **Upload Example to Your Board**
   - For Arduino: Open the `.ino` file in Arduino IDE and upload to your board.
   - For STM32: Use your preferred development environment to compile and flash the `.c` example.

4. **Wiring**
   - Check the `notes.md` file in each sensor folder for wiring diagrams and instructions.

## Requirements

- Arduino IDE or STM32 development tools
- The sensor and compatible microcontroller
- Basic wiring tools

## Troubleshooting

- Ensure correct wiring and power supply
- Consult datasheets (linked in `notes.md`) for pinouts and specs
