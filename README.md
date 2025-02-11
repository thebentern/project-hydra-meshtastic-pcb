# Project Hydra (Meshtastic PCB)

[![Build Artifacts](https://github.com/PlumRugOfDoom/project-hydra-meshtastic-pcb/actions/workflows/build-release-artifacts.yml/badge.svg)](https://github.com/PlumRugOfDoom/project-hydra-meshtastic-pcb/actions/workflows/build-release-artifacts.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


A minimalist PCB design built around the Ebyte E22-900M30S 30dbm (1 watt) LoRA radio and the ESP32-WROOM-32U mpu compatible with the [Meshtastic-device](https://github.com/meshtastic/Meshtastic-device) firmware. 

![image](https://user-images.githubusercontent.com/9000580/140797732-4bd02f65-b526-48d9-92bb-ef328034113d.png)

## Features
- Supports up to 30dbm (1 watt) transmit power
- OLED support via I2C
- GPS support via UART
- PSRAM support
- User button via pin header
- Switchable 3.3V power rail (GPS power saving)
- ADC input for battery voltage sensing
- Single 5V input (no reverse polarity and overvoltage protection!)
- 3.3V output (or input if onboard buck converter is not assembled)
- Two GPIO reserved for future use (for example power control)
- Programmable via USB-Serial adapter (RTS/DTR are required for the on-board auto reset!)
- Compatible with "meshtastic-diy-v1" target

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/PlumRugOfDoom/project-hydra-meshtastic-pcb/compare/).

## Support

Please [open an issue](https://github.com/PlumRugOfDoom/project-hydra-meshtastic-pcb/issues/new) for support.

## License
[MIT](https://choosealicense.com/licenses/mit/)

[Meshtastic](https://meshtastic.org/)® is a registered trademark of Geeksville Industries LLC. Meshtastic software components are released under various licenses, see github for details. No warranty is provided - use at your own risk.
