---
title: "PortaHost"
author: "tharakeshrajesh"
description: "An offline game server that can be connected through Wi-Fi"
created_on: "2025-06-16"
---

# 06/18/2025
Changed name from "Offline-Game-Server" to PortaHost

# 06/19/2025
Searched up some parts:
* [Raspberry Pi 5 \(don't know how much RAM yet\)](https://vilros.com/products/raspberry-pi-5)
* [Raspberry Pi 5 cooler](https://www.aliexpress.us/item/3256806484520621.html)
* [SPI TFT LCD Display Module](https://www.aliexpress.us/item/3256805953674718.html)
* [50 ct. Tactile Push Buttons](https://www.aliexpress.us/item/2251832629654875.html)
* [KY-023 Joystick Module](https://www.aliexpress.us/item/3256808899611893.html)

# 06/28/2025
I decided not to use the Raspberry Pi 5 and to use its compute module version instead to make it less bulky and more portable.
Also added the MIT license yesterday.
Found some footprints and stuff:
* [DF40 Connector](https://app.ultralibrarian.com/details/4330ca74-5bcc-11ea-8c00-0ad2c9526b44/Hirose/DF40C-100DS-0-4V-51-)
* [LCD Display](https://github.com/dishishshawn/kicad-st7735s-1.8in-tft) but I had to edit it to work with the [LCD I am using](https://www.aliexpress.us/item/3256805953674718.html).
I also decided not to use joysticks and to replace it with a switch rotary encoder instead.

# 06/29/2025
Finished schematics and PCB and added more libraries.
The DF40 connector's pins are too close to each other so I couldn't get the wires on the PCB to connect to them so I will have to hand solder that.
May fix that issue later, probably not...
Also added USB-C power receptacle which I didn't yesterday. I forgot to add on yesterday that I was half done with schematics but now you know.

# 07/4/2025
Okay, I am back from inactivity. But today was not pleasant.

![image](https://files.slack.com/files-tmb/T0266FRGM-F094U53PU81-532357941e/image_480.png)

230 errors and 12 warnings.
Fortunately I fixed most of them since they were just clearance errors and wiring warnings with the DF40 pads/pins and LCD pads. I also finished wiring everything including LCD because apparently I forgot that last time but anyways...
I need to add an external antenna next.
