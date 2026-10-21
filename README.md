# AeroBlinker
Custom PCB w/ KiCAD that reads Receiver Signals to control light flash patterns - Aeronautics Team.

Read [JOURNAL.md](https://github.com/toyJig/AeroBlinker/blob/main/JOURNAL.md) for the logged process!

<img width="513" height="334" alt="image" src="https://github.com/user-attachments/assets/e7677326-788c-4ba5-908d-73313c869b29" />

| Features: |
| -------- |
| A small STM32F042F6P6 MCU that decodes PWM frequencies to control a MOSFET |
| USB-C flashing and a LDO regulator for the USB-C VBUS (the STM can't handle 5V) |
| An on-board 3.3v Buck Convertor to step down efficiently from 1S or 2S Voltages |
| Connectors to connect up to 3 LEDs with (Can wire more in series if needed) |

<img width="654" height="468" alt="image" src="https://github.com/user-attachments/assets/b7071b7f-a524-4b5a-ba0b-97c8dab67d2c" />
