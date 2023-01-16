View this project on [CADLAB.io](https://cadlab.io/project/26395). 

# BGMP220P Breakout Board

## What's this?

A breakout board for Silicon Labs BGM220P bluetooth modules.

<p align="middle">
  <img src="/support/img/BGM220P_Breakout_Front.png" width="35%" />
  <img src="/support/img/BGM220P_Breakout_Side.png" width="43.5%" />
</p>

It's made with both WGA and HNA variants (352KB and 512KB flash sizes) in mind.

## How to use it?

### Making some

Gerbers should be available in the Releases section. Just grab them and print them. Keep in mind that it's a four layer board, and not all the cheap PCB manufacturers offer stupidly cheap 4 layer PCBs (although some do, and those who don't offer relatively cheap 4 layer boards).

Soldering is straightforward as pads have been extended for easier hand-soldering. A stencil made from these gerbers should only leave paste in part of the pads (by design). While I haven't tested it, it should be enough for hot air reflow or hotplate soldering.

### Add the target /  receptacle to you project, so you can add the module to your project.

The project includes a library with the "receptacle", two 1x16 headers spaced the required amount of distance. Place that in your board and plug your breakout. Alternatively, don't place headers, align hole to hole and apply solder.

<p align="middle">
  <img src="/support/img/BGM220P_Breakout_Receptacle_Side.png" width="43.5%" />
</p>
