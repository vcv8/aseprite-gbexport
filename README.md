# Gameboy Export for Aseprite (XFirst)

Modification of [boombuler](https://github.com/boombuler/aseprite-gbexport) script to read tiles in X axis first.

## Installation

Just copy `GameboyExport.lua` to your aseprite script directory. After that you can export the current sprite to gameboy assembler files.

## Sprite constraints

* The width and height must be a multiple of 8 pixels.
* It must be an indexed file.

## Example
boombuler reading order |  XFirst reading order
:-------------------------:|:-------------------------:
![boombuler reading order](https://i.imgur.com/N0FRxasl.jpg) | ![XFirst reading order](https://i.imgur.com/SyP2ES8l.jpg)
