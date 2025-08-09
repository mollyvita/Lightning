# Lightning
An Ultrahand package designed for managing charging amperage on the Nintendo Switch. It's helpful for consoles with modified batteries, as it allows them to charge faster than default.
Russian README is located [here](README_RU.md).

> [!CAUTION]
> This package CAN and probably WILL cause issues on high values, such as PCB heating more than it should or battery not charging to the full capacity.
> I am NOT responsible for that.
> Use ONLY ___if you know what you're doing.___

## Configuration
The `package.ini` file contains the following configurations:
- `Charge amp`: Change charging amperage for your console.
- `Reset`: Restore default value.
- `Complete (Reboot)`: A quick shortcut for rebooting, which is required to apply the changes.

### Amperage values:
- 1024 mA
- 1280 mA
- 1536 mA
- 1660 mA (Default for Switch Lite)
- 1792 mA
- 2048 mA (Default for Rev 1 and OLED)
- 2304 mA
- 2560 mA
- 3072 mA (Extreme value! Be **especially** careful with this one.)

> [!WARNING]
> BE CAREFUL WITH THE PCB'S TEMPERATURE AND BATTERY!

## Installation
To install `Lightning`:
1. Get the latest release [here](https://github.com/mollyvita/Lightning/releases/latest).
2. Unzip the archive to `/switch/.packages`.

## Credits
This project was possible thanks to @ppkantorski and their [Ultrahand](https://github.com/ppkantorski/Ultrahand-Overlay) overlay. Check it out! :)
