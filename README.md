# Smart-Blinky

This is an Pathfinder Project which will runs leds in such a sequence that it blinks in a coded pattern using a pcb, some buttons and an XIAO RP2040

Softwares used: KiCad, Google Chrome, Arduino(2.3.8) 

Simple PCB which uses some 5mm - LEDs, XIAO RP2040 Arduino, MX Key Switches, generic keycaps and 68ohm resistors.
In my case i will use 3 buttons and 3 leds so 3 of each except the RP2040.

Here is what each button is supposed to do:


Button 1 - Blinks any random LED using random()


Button 2 - L2-(L1+L3) sequence


Button 3 - Complex animation effect


The Arduino Codes can be found in the File named "Arduino Codes" attached in this github repo! 

The Gerber file/s can be found directly in the main branch or "KiCad Files" Folder




# **Photos:**


Schematics:
<img width="1180" height="542" alt="Schematics" src="https://github.com/user-attachments/assets/b7c2103e-d914-44dd-ad4c-68346143e9a8" />



PCB Layout:
<img width="1180" height="680" alt="PCB Layout" src="https://github.com/user-attachments/assets/c6484e34-8b97-46c2-8c26-6a3fe5fdbded" />


PCB 3D Front View:
<img width="1165" height="734" alt="PCB 3D Front View" src="https://github.com/user-attachments/assets/d0d0850a-4796-4faf-bb8f-ea124ff10936" />

PCB 3D Back View:
<img width="1102" height="693" alt="PCB 3D Back View" src="https://github.com/user-attachments/assets/6d2dce9a-769d-42ed-96ba-a347d520be6d" />

Bill Of Material:

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|----------|----------|----------|----------|----------|----------|
| Cherry MX2A Switch (10) | Keyboard Switch | 1 | 4.6 | https://meckeys.com/shop/accessories/keyboard-accessories/key-switches/cherry-mx2a-switch/?attribute_pa_cherry-mx=blue-rgb | Mac Keys |
| Blank DSA Keycaps (5) | Keyboard Keycap | 1 | 1.1 | https://meckeys.com/shop/accessories/keyboard-accessories/keycaps/blank/blank-dsa-keycaps-1u/?attribute_pa_variations=off-white | Mac Keys |
| 5mm Blue LED (10) | LED for blink blink o_0 | 1 | 0.25 | https://thinkrobotics.com/products/5mm-led-pack-of-10?variant=12744149205064 | Think Robotics |
| 5mm Green LED (10) | LED for blink blink o_0 | 1 | 0.25 | https://thinkrobotics.com/products/5mm-led-pack-of-10?variant=12744149205064 | Think Robotics |
| 5mm Red LED (10) | LED for blink blink o_0 | 1 | 0.25 | https://thinkrobotics.com/products/5mm-led-pack-of-10?variant=12744149205064 | Think Robotics |
| Seeed Studio XIAO RP2040 | Brain I would say | 1 | 5.8 | https://thinkrobotics.com/products/seeed-studio-xiao-rp2040?variant=47933480173885&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&utm_source=googleads&utm_medium=cpc&utm_source=SR_google&utm_medium=Shopping&utm_campaign=SR467_ShoppingAds_Category-23015774368&utm_content=-293946777986&gad_source=1&gad_campaignid=23015774368&gbraid=0AAAAACk3EvwNg85ivfXz7_douBtysfEe2&gclid=Cj0KCQjwrZTRBhDSARIsAHidYfc42TlNvgxk9vyaR3ITMNI-v1SkI1oklDQBm8kxzEVwLjYCuWwf5FUaAjsrEALw_wcB | Think Robotics |
| 68 Ohm 1/4 Watt Resistor with 1% Tolerance (10) | Resistance for LEDs | 1 | 0.11 | https://quartzcomponents.com/products/68-ohm-1-4-watt-resistor-with-1-tolerance-pack-of-10?variant=45769223897322 | Quatrz Componenets |
| PCB | "Mother"- Board | 1 | 13.55 | https://www.lioncircuits.com/cart | Lion Circuits |
