# FLSUN QQ klipper configuration

This repository contains the klipper configuration for my FLSUN QQ printer.

## Notes

- You'll have to be creative in order to use the USB leveling plate provided by FLSUN: Since Klipper occupies the USB port of the printer, you cannot connect the leveling plate to USB. You could connect the ground shield of the leveling plate's USB connector to a grounded part of the connected Raspberry Pi, e.g. the metal shield of the USB or Ethernet sockets.

- The MKS TFT display will not work together with Klipper. You'll have to disconnect it from the MKS GEN L board.
