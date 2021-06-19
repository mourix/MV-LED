# MV-LED Reproduction
This is a complete reverse engineering and redrawing of the SNK MV-LED credit counter board. When I restored my Neo Geo cab I found out the prices of these boards are starting to skyrocket. I got myself a damaged MV-LED, scanned the stripped PCBs and figured out the schematics from there. The result is a working copy of the original board you can order and assemble yourself!

![MV-LED_altium](https://raw.githubusercontent.com/mourix/MV-LED/main/Pictures/MV-LED_altium.jpg)

# How do I make one?
## Bill of Materials
You need the following items for one unit:

|Part|Amount|
|--|--|
|220uF 10V polarized capacitor|1|
|100nF 50V ceramic capacitor|4|
|CRE401 RRC array|3|
|LB-602VA2 display|1|
|JST BS13P-SHF-1AA|1|
|Resistor array 330R|4|
|74HC273|1|
|74HC14|1|
|74LS47|2|
|MV-LED PCB|1|

![MV-LED_assembly](https://raw.githubusercontent.com/mourix/MV-LED/main/Pictures/MV-LED_assembly.jpg)

## PCB
The MV-LED is a 150x40mm 1.6mm PCB. I used JLCPCB rules, but these gerbers will probably work with your fab.

## CRE401
The CRE401 RRC array is out of production, but I got you covered! [Check out the CRE401 Reproduction.](https://github.com/mourix/CRE401)
