Practical Arduino USB Host Shield
=================================
Copyright 2010 Jonathan Oxer <jon@oxer.com.au>  

Shield for Arduino Duemilanove microcontroller and other boards based
on the same header format, such as the Seeeduino and the Arduino Pro.

Connects a Vinculum VDIP1 USB controller module to the Arduino via SPI.
The SPI select address can be jumpered against any of digital I/O pins
5 through 10.

Includes prototyping area using the spare shield area.

Features:

 * Mounting pads for Vinculum VDIP1 USB host module.
 * Second USB port from VDIP1 brought out on the PCB.
 * Prototyping area.
 * Reset button wired through to Arduino reset pin.
 * Power-on indicator LED.


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> ProtoShield.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).


FABRICATION OPTIONS
-------------------
If you haven't had PCBs fabricated before it can be very confusing
trying to work out all the options. We have our boards fabbed by
pcbcart.com, so to save you some hassle the list below shows our
recommended selections for the options on their order form. Some of the
settings can be changed if you have different preferences but this is a
sensible starting point if you don't know what the options mean and
should result in a decent board.

Note that the colour options below are for a yellow board with black
text, and with all exposed surfaces gold-plated for maximum durability.

 * Material:                 FR4
 * Layers:                   2 Layer
 * Material Details:         Standard Tg 140C
 * Part Number:              PA_SHIELD_USBHOST (or substitute your own)
 * Board Type:               Single Unit
 * Board Size (width):       59.69mm
 * Board Size (height):      53.34mm
 * Quantity:                 Select as appropriate
 * Thickness:                1.2mm
 * Surface Finish:           ENIG (gold)
 * Copper Weight (Finished): 35um
 * Min. Tracing/Spacing:     0.20mm    (8 thou)
 * Min. Annular Ring:        0.30mm    (12 thou)
 * Smallest Holes:           0.40mm
 * Holes Numbers:            <300
 * Surface Mount:            1 side
 * Soldermask:               Both sides
 * Peelable Soldermask:      None
 * Soldermask Color:         Yellow
 * Matt Color:               None
 * Silkscreen Legend:        2 sides
 * Silkscreen Legend Color:  Black
 * Gold Fingers:             No
 * Gold Fingers Number:
 * Gold Fingers Chamfer:
 * Slots in Board:           No Slot in Board
 * Slots quantity in board:
 * Testing:                  Yes
 * UL Marking:               No
 * Date Code Marking:        No
 * Lead Time:                8 or 12 days, as you prefer (8 costs a small amount more)
 * Special Requirement Note: PCB is routed to outside of Top layer
