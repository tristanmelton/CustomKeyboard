### Custom Keyboard and Numpad - Beryl.
I had some problems with Amethyst, namely:
- USB-Micro instead of USB-C
- Wired takes up an already-limited USB slot
- A little tall to type on
- Non-customizable key switches

So for Beryl, I'm proposing:
- USB-C with the nice!nano microcontroller. Also covers wireless with the built-in bluetooth.
- Going to use Kailh switches with low-profile to shorten the height, with hot-swap sockets.  

### Changelog
## 1/25/2025
I did some initial re-organization and copied the v1 to a v2 folder for initial setup. The MCU was replaced with a nice!nano and I'm using hot-swappable Kailh choc switches now.
Board should be laid out and everything - it's been sent off with JLCPCB.

PURCHASED:
- PCB x5 from JLCPCB
- Battery from Amazon
- Kailh hot-swappable sockets x100 from AliExpress
- nice!nano v2 x5 from AliExpress
- JST Connector from Digikey
- Sliding switch from Digikey
- Kailh Low Profile Choc Switches (red) x80 from Typeractive

I only have not ordered Keycaps yet. If you have any suggestions please let me know.

## 2/11/2025
I have updated the PCB with a silly mistake that had GND and VCC swapped on the battery. The software is complete and can be found (https://github.com/tristanmelton/cheapino-zmk-config-single-nicenano). The direct uf2 is also in the Software folder.