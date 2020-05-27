# EP + OCD v2

This is an EP Booster and OCD v2 in a single 125 enclosure.

[You can buy a PCB here](https://mas-effects.square.site/product/ocd-ep-booster-board/19?cp=true&sa=true&sbp=false&q=false). Alternatively this repository contains everything you need to build it on your own.

![picture of the EP+OCD pedal](EP-OCD.jpg)

# Assembly

Sorry I don't have a detailed assembly guide, and probably won't write one, but email me if you have questions: mark@mas-effects.com

If you fabricate your own PCBs from the gerber files, they should work without modification.  But if you purchased a PCB from me there are 2 important fixes to make:

## Fix 1: Boost Pot

1. Cut off leg 2 of the boost pot. i.e. don't connect it to the board.
2. Solder a jumper from leg 2 to leg 1

![picture of the boost pot pic](assembly/boost-pot-modification.jpg)

## Fix 2: Missing trace

Solder a jumper wire from the base of Q2 to middle leg of the SW2 (bright switch).

![picture of jumper wire](assembly/jumper-wire.png)

