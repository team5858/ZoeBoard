# Building the Zoe Board

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/zoeBoard.jpg" width="500">

You will need the following tools:

### Soldering Iron
<img src="https://github.com/team5858/ZoeBoard/blob/master/art/iron.jpg" width="200">

### Solder
<img src="https://github.com/team5858/ZoeBoard/blob/master/art/solder.jpg" width="200">

### Needle Nose Pliers
<img src="https://github.com/team5858/ZoeBoard/blob/master/art/needle.jpg" width="200">

### Wire Snips
<img src="https://github.com/team5858/ZoeBoard/blob/master/art/snips.jpg" width="200">


# 74HCT125 Level Shifter

The LED strips need 5V logic signals. The propeller provides 3.3V signals. This chip converts the four output lines to 5V.

  - Place the chip into the holes of the board as shown.
  - You will need to bend the pins inwards a bit to get them to fit. Use needle nose pliers to bend the pins slightly.
   
**Important: the notch in the chip goes near the top of the board.**

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct01.jpg" width="300"> <img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct02.jpg" width="400">

  - Turn the board over and solder the pins to the board. 
  - Take a break between every couple of pins to let the heat drain away.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct03.jpg" width="500">

# Propeller Mini

The Propeller Mini is the brains -- the controller that drives the LEDs.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct04.jpg" width="400"> <img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct05.jpg" width="400">

  - Push the 4 pin programming connector through the top of the blue propeller board. 
  - Turn the propeller board over and solder the pins in place. 
  - Use wire snips to trim the pins down flush with the board. 
  
**Watch your eyes! Those snipped pins might fly into your face.**

TODO change this picture to show long pins through.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct06.jpg" width="400"> <img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct08.jpg" width="400">

  - Place the pin headers into the Zoe board. The long side of the pins goes through to the bottom of the board. 
  - Place the blue propeller board onto the pins. The programming pins will hang over the URL on the board.
  - Now solder the header pins to the top of the blue propeller board and to the bottom of the Zoe board. 
  - Take a break between pins to let the heat drain away. 

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct07.jpg" width="400">

  - Use wire snips to trim the pins on the bottom of the board as shown. 

# "Buck" DC-DC Converter

The Zoe board needs a steady 5V power supply. The Buck convert connects to the robot battery (12 V) and provide
a steady 5V supply to the electronics on the Zoe board.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct09.jpg" width="400"> <img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct10.jpg" width="400">

  - Carefully solder the Buck converter's 4 wires through the holes in the Zoe board. 
  - The large red wire will be near "VIN". 
  - The smaller red wire should be near "5V".

# Resistors

The Zoe board has five resistors. R1 through R4 are the same value. You will find these four grouped together in a
tape reel. R5 is a single resistor with tape nubs on each pin.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct11.jpg" width="400"> <img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct12.jpg" width="400">
 
  - Bend the pins and push them through the pads for R1 through R4. 
  - The direction doesn't matter -- there is no "backwards".

R5 is the single lone resistor that goes near the top of the board by the Buck converter. 

  - Solder the pins on the bottom of the Zoe board. Use wire snips to trim the pins.

# Capacitors

There are two capacitors: C1 and C2. They are the same value. 

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct13.jpg" width="400">

 - Wiggle the pins through as best you can. They don't fit perfectly. 
 - The direction doesn't matter -- there is no "backwards".
 - Solder the pins to the bottom of the Zoe board. 
 - Trim the pins flush to the board.

# Power LED

The green LED lights up when the Zoe board is powered.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct14.jpg" width="400"> <img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct15.jpg" width="400">

  - Push the LED pins through the board. 
  
**Important: the long pin of the LED goes through the square pad. The short
pin goes through the round pad. The LED's flat edge should match the flat edge on the symbol on the board.**

  - Turn the board over and solder the pins in place. 
  - Snip the pins flush.

# Connectors

There are four connectors on the right side of the board. These are for the NeoPixel strips. 

The power connector on the left side of the board provides 9V-12V from the robot.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct16.jpg" width="400">

Each connector has a mate. The connectors you attach to the have the shorter wires. The matching cables that connect to the robot are shown above the board in the photo.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct17.jpg" width="400">

  - Solder the four pixel connectors to the right side of the board.
  - The red wires go in the 5V holes
  - The green wires go in the data holes (D1, D2, D3, or D4)
  - The white wires go in the GND hole
  
** Note: these holes are much bigger than the wires. You should fill the entire hole with solder. **

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct18.jpg" width="400">

  - Turn the board over and trim the wires flush to the board

# Serial Connector

The serial connector allows the robot to send commands to the Zoe board.

<img src="https://github.com/team5858/ZoeBoard/blob/master/art/construct19.jpg" width="400">

  - Solder the black wire to GND
  - Solder the white wire to S2
  - Solder the gray wire to S3
  
The S4 and S5 pads are for future use.
