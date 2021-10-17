# z12

## Description
The z12 is a mechanical micropad with 6x MX/Choc v1&v2 switches, 4x 6x6mm momentary buttons, 2x EC11 rotary encoders and 1x 128x32 OLED display. It uses no diodes.

## Main use
This layout allows me to configure shortcuts and rotary encoder actions for several apps (i.e. sketch, terminal, browser, ...).

With the use of my [active-app-qmk-layer-updater](https://github.com/zigotica/active-app-qmk-layer-updater) script I can even change layers automatically when moving across apps in the operating system, no need to press a switch to change layer anymore. Go have a look.

## Images
See high res pictures clicking the images on this gallery:

![z12](./images/z12.jpg)

![z12-top](./images/z12-top.jpg)

![z12-board](./images/z12-board.jpg)

![z12-board-back](./images/z12-board-back.jpg)

## Build
You can build your own pad using the gerber shared in this repo. Just zip the folder and send to your favourite online shop. I use [JLCPCB](https://jlcpcb.com/) and quality is really nice for the cost (and that black matte is gorgeous). No plate has been designed yet (misalignments are really visible in the images above, due to the fact I used 3 pin switches), but it is under development. 

## Firmware
You can play around your desired keymap using [QMK online configurator](https://config.qmk.fm/#/z12/LAYOUT) or manually writing your changes to the keymap either in  your username folder or adding a folder to the [z12 official firmware](https://github.com/qmk/qmk_firmware/tree/master/keyboards/z12).
