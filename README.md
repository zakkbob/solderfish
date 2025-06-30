# Solderfish
My first PCB! It has a button and some LEDs :O

# Schematic
It's very simple, when the button is pressed, the LEDs _should_ turn on, and then the potentiometer will change the brightness.
![Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e2bf726b9ed22369a666697acea4a0fe3f12cdda_2025-06-30-205753_hyprshot.png)

# PCB
Also, it's supposed to look like a fish.

![Front of PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/b04081e4f44bf14f8269172ce6372077703567a3_2025-06-30-205720_hyprshot.png)
![Back of PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a9040cfc3c5408375cc19f8761be2c5e34f625df_2025-06-30-205739_hyprshot.png)
![3D PCB](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2d17ad161dcf5653cc0f9e8837b1fe2a676e3637_2025-06-30-205636_hyprshot.png)

# Simulation
Here is the [Falstad Simulation](https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAUgpABZsKBTAWjDACgBncYlEbXzL35QRAMwCGAGw4M2AN268wGQor68qVGlSSao0BG2U0Qg9eqpgUecMjj7+YPPBev6AJQYcAlhwAu4gB2AMayYIRCeCbC2FEgxKq8ACYMEgCukn5MkgxJtnowkOzhvDQ0NsJlNgmmICnpmdm5+SKF7ABOtOXgKl3VqlTYuGydsSY1Yz0DfMMA7mrKiRhKvZBs82aLpsvg1lDr2yuqk1tr8ye9VVP781cxccJnFiDOfAi8r0-Y7y+DP48Hb5CSLRDRsIA)

# Features
- Low power! Only 3V
- Contains the [Hacklet](hacklet.hackclub.com) logo :O (My first YSWS)
- Random bits of text I added
- Super cool fish shape

# BOM
| Value | Qty | Reference | Footprint |
| ----- | --- | --------- | --------- |
| Battery_Cell | 1 | BT1 | Battery:BatteryHolder_Keystone_3034_1x20mm | 
| LED | 2 | D1,D2 | LED_THT:LED_D5.0mm | 
| R | 2 | R1,R2 | Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | 
| SW_Push | 1 | SW1 | Button_Switch_THT:SW_PUSH_6mm |
| R_Potentiometer | 1 | RV1 | Potentiometer_THT:Potentiometer_Vishay_T73YP_Vertical |


Made by @zakkbob on slack :D

Made for [Solder](https://solder.hackclub.com), a [Hack Club](https://hackclub.com) program where you make your first circuit board and get a kit of electronics to assemble it for free!
