# Mechboard64BracketFiles
Files to assist in making the open-hardware metal bracket for the Mechboard64

## What is Mechboard64?
Taken from breadbox64.com, the author of Mechboard64. ([link](https://www.breadbox64.com/blog/diy-mechboard64/))

The MechBoard64 is a drop-in replacement mechanical keyboard for your original Commodore 64 home computer. It will work in concordance with all the different versions of motherboards available, including the new motherboards (C64 Reloaded MK1+2 and Ultimate64). The MechBoard64 is based on quality microswitches, a sturdy aluminum bracket, a printed circuit board (PCB) and a multicolored ribbon cable for connecting the keyboard to the C64 hardware. The MechBoard64 also has a small electrical circuit that will add the functionality of the Shift Lock key but without the need for a latching microswitch like the Cherry Locking switch. Whenever the Shift Lock key is pressed, a bright LED will light up underneath the keycap to indicate its current state (on or off).

Description on what parts are needed to complete the MechBoard64 build can be found here: ([link](https://www.breadbox64.com/blog/diy-mechboard64/))
Assembly instructions can be found here: ([link](https://www.breadbox64.com/mechboard64-2/mechboard64-assembly-instructions/))
Heaps of images can be found here: ([link](https://www.breadbox64.com/blog/the-mechboard64/))

### 3D rendition files
In addition to the bent-metal version of the Bracket, user [IndigouFox](https://www.thingiverse.com/indigoufox/designs) came up with a 3D printed version of the same bracket, [available on thingiverse](https://www.thingiverse.com/thing:5448321). This file comes in useful too.

# What is this current set of files?
Here are files to help in having the open-hardware metal bracket of the Mechboard64 produced. An issue when trying to have the metal bracket produced is that manufacturers don't all want the same data the same way. [MtnBuffalo](https://www.pcbway.com/project/member/?bmbno=67FED125-1063-4F) rendered public the files he used when making his own brackets - currently v.1.07 - and the files are available [on his blog](https://www.breadbox64.com/blog/diy-mechboard64/).
The metal brackets are in the subfolder metal bracket of [the ZIP file he made available](https://www.breadbox64.com/wp-content/uploads/2021/04/DIY_MechBoard64_107LED_Mod.zip).

After much discussions when trying to get the brackets manufactured, we ended up coming up with a set of files that should help in making the process easier, and decided to make them available here.

## What are the files
Based on the MtnBuffalo bracket files, we can get so far. 

### Base package
Most of the files are directly taken from v.1.07 from breadbox64. Thanks MtnBuffalo.

### faceplate
However, precise measurements of the key switch holes on the front plate can be problematic. The solution is to propose IndogouFox's file that has a 3D rendition of same faceplate. They needed it in .STP so we converted it to a step file using an online converter.

### Mounting area
Another area of contention is the mounting holes. Not wanting approximations they demanded something more precise than the .AI file. I came up with measurements and made an updated technical drawing specifying hole positionning and measurements.
