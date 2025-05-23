# View-Remaster
For this project, I made a View-Master Reel scanner.
I call it the View-Remaster. In short, this will scan in 3D View-Master reels and create a side-by-side (SBS) video that I can upload to YouTube.

I've been wanting to do this project for a VERY long time. So I'm excited to share it with you.

The channel that the video are uploading to are here:
https://www.youtube.com/channel/UCOirfwqCtgHvdcQz5gyFoTg

The build video is here:
https://youtu.be/6Y3vohi8WqI


# EDITS:

List of materials:

Bearing MF115ZZ:
https://www.aliexpress.com/item/1005007978162977.html

Google cardboard googles:
https://www.aliexpress.com/item/1005006466981096.html

Optical end stop sensor:
https://www.aliexpress.com/item/1005002219411174.html

Aluminium rod 12mmx300mm:
https://www.aliexpress.com/item/1005007360272645.html

Magnets 6x2mm:
https://www.aliexpress.com/item/1005008053185179.html

Motor 5V 4-Phase 28BYJ-48 DC Gear Step Stepper Motor+ULN2003 Driver Board:
https://www.aliexpress.com/item/1005006239720269.html

LED Adafruit Industries NeoPixel Jewel - 7 x 5050 RGBW LED w/Integrated Drivers
or alternative:
https://www.aliexpress.com/item/1005001693824089.html


         7 bit ws2812:
         https://www.aliexpress.com/item/1005007268165626.html or https://www.aliexpress.com/item/1005001693824089.html

         24 Leds ring
         https://www.aliexpress.com/item/1005002286128420.html

         Simple 3W 24mm Warm, no Wire
         https://www.aliexpress.com/item/1005006126055318.html



HD CS 5-50mm Varifocal Lens Industrial 30fps 4K 8MP CCD IMX415 USB Webcam:
https://www.aliexpress.com/item/1005008657226691.html

Extension tubes:
https://www.aliexpress.com/item/1005004909394341.html

MosFET trigger:
https://www.aliexpress.com/item/1005008217485311.html

Lamp:
https://www.aliexpress.com/item/1005003057943564.html


# Connection:

         VCC (5V) <> Led+
                  <> Sensor V
                  <> Stepper 5V+

         GND      <> LED-
                  <> Sensor G
                  <> Stepper 5V-

         Data ports:
         PD02     <> Stepper In1
         PD03     <> Stepper In2
         PD04     <> Stepper In3
         PD05     <> Stepper In4
         PD06     <> Sensor S
         PD07     <> LED in
         PD10     <> Lamp on/off
         PD11     <> Lamp light temperature


![Untitled Diagram drawio](https://github.com/user-attachments/assets/3c37552f-7285-439a-ae26-c830aa69db42)




# STL Changes

ReelSupport v18

        Merged Reelsupport v17 with helical ring gear

Helical gear v3

        Separated helical gear

BearingHolder v5_MF115ZZ

        BearingHolder v4 adjusted for use with bearing MF115ZZ

MasterReelBase adjusted (v27)

        for use with bearing MF115ZZ
        7bit light (diameter 25mm)
        holes for M3 bolts
        seat for m3

Camera_base v4 and Camera_base_Reel v5

        holes for M3 bolts
        seat for m3
