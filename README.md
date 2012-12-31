# GlovePIE script for playing Diablo II with Wiimote and Nunchuck
## Overview
My wife is a big fan of [Diablo II](http://en.wikipedia.org/wiki/Diablo_II), in order to play this 10+ year old game with her, I have to introduce some extra fun by controlling the game with the Wiimote I happen to have.
## Setup
* Install [GlovePIE](http://glovepie.org/glovepie.php), which is a driver program for the Wiimote
	* I install GlovePIE v0.45
	* I install it under Windows 8 in my MacBook through BootCamp
* Connect Wiimote to the PC
	* You need to have a Bluetooth adapter installed in your PC, and I use the built-in Bluetooth adapter in my MacBook, which works well with Wiimote. 
	* Not all Bluetooth adapter can work with Wiimote, check [this page](http://wiibrew.org/wiki/List_of_Working_Bluetooth_Devices) if necessary
	* Add a new Bluetooth device in Windows, with Wiimote's "1" and "2" buttons pressed symutaneously
	* Open GlovePIE, and switch to "GUI" tab. If Wiimote is connected successfully, the LED "1" and "4" in Wiimote will be lighted (If you switch from the GUI tab, and don't have any GlovePIE script running, GlovePIE will turn off your Wiimote for power saving, and it should be automatically turned on when necessary).
	* You should be able to see a button called "Detect Input" in GlovePIE, once clicked, press any key in your Wiimote, and GlovePIE should be able to detect the input from Wiimote and show it to you
* Start Sensor Bar of Wii
	* This script requires the use of Wii's Sensor Bar to allow Wiimote to be used as an IR mouse
	* You need to start Wii with the Sensor Bar connected
	* I found when Wii is started, the Wiimote will auto disconnect from the PC and re-connect to the Wii, in this case, you have to press the "Sync" button near Wii's SD card slot for more than 10 seconds to reset all the remotes and delete all Wiimote information from this Wii
	* Just in case your Wii is [homebrewed](http://wiibrew.org/wiki/Homebrew_Channel), I found if the Wii is started and enters the Homebrew Channel screen, the Sensor Bar will not be powered and started. You have to press the "reset" button in Wii to make it enter the original startup screen of Wii instead of the initial screen of Homebrew channel
* Run the script
	* Open the diabloii.PIE script via GlovePIE, and start to run the script
* Launch Diablo II
	* For running Diablo II under Windows 8, you have to run it under Windows XP SP3 compatability mode, and with "Disable display scaling on high DPI settings" checked (I mirrored my MacBook's screen to my 46 inches TV)
* Start playing

## Control mapping
| Game function | Original Game Input | Wiimote & Nunchuck Input |
| ------------  | ------------- | ------------   |
| Health potion	 | keyboard.1 | shake nunchuck |
| Health potion	 | keyboard.2 | shake wiimonte |
| Magic potion	 | keyboard.3 | nunchuck.joystick.up |
| Health potion	 | keyboard.4 | nunchuck.joystick.down |
| Movement      | Mouse pointer		| wiimote + sensor bar |
| Close/Option  | keyboard.escape	| wiimote.home + nunchuck.Z |
| Town portal   | keyboard.F4		| wiimote.CircleClockwise gesture (draw a circle with your Wiimote) |
| 2nd secondary skill | keyboard.F2         | wiimote.CrossArms gesture (mapped to transformation skill of Druid intuitively) |
| Show dropped items  | keyboard.Alt			| nunchuck.Z |
| Stay still          | keyboard.Shift		    | nunchuck.C |
| Show equipped arms  | keyboard.b				| wiimote.home |
| Primary skill	       | mouse.leftClick	    | wiimote.B |
| Secondary skill     | mouse.rightClick	    | wiimote.A |
| 1st secondary skill | keyboard.F1			| wiimote.1 |
| 2nd secondary skill | keyboard.F2			| wiimote.2 |
| 3rd secondary skill | keyboard.F3			| wiimote.minus |
| 4th secondary skill | keyboard.F4			| wiimote.plus (mapped to town portal) |
| 5st secondary skill | keyboard.F5			| wiimote.dpad.left |
| 6st secondary skill | keyboard.F6			| wiimote.dpad.down |
| 7st secondary skill | keyboard.F7			| wiimote.dpad.right |
| 8st secondary skill | keyboard.F8			| wiimote.dpad.up |
