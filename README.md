# The Lion

IDE: [PlatformIO](https://platformio.org/)

## MAX7219 8x8 LED matrix

The library I use: [github.com/MajicDesigns/MD_MAX72XX](https://github.com/MajicDesigns/MD_MAX72XX)

Pico GPIO | SPI                   | MAX7219 |
--------- |-----------------------|---------|
GP19      | TK/MOSI               | DIN
GP18      | SCK Serial Clock      | CLK
GP17      | CSn Chip/Slave select | CS
GP16      | RX/MISO               |
VBUS (5V) |                       | VCC (5V)
GND       |                       | GND

## Links

- [Serial Pin Names](https://en.wikipedia.org/wiki/Serial_Peripheral_Interface)

____

Tauno Erik 2022
