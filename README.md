# OLED Motivational Lock Box

This project was built prior to enrolling in the Flatiron Software Engineering Program.  This was a project done as a hobbyist, with a goal of making a pairing of software and hardware that could help improve peoples habbits.

The code within this repo is intended to be installed on an ESP8266 board.

The program utilizes a library for an Adafruit OLED display, 128x64px with i2c connection protocols. there are cheaper clones of this display available online.  I personally used the blue & yellow oled screen version.

It also utlizes a 5v power supply, capable of being powered off a standard USB 500mah supply (very low power), a single pole relay, and a small 5v solenoid.  The ESP8266 program is downloaded, populated with your wifi credentials, and wired up with the relay & solenoid.  Once connecting to the wifi network, the display will show the devices IP address.  This IP address needs to be entered into the companion phone app.  After completion, the checklist application makes the corresponding call to the ESP8266 and the 'open' route triggers the relay briefly causing the solenoid to unlock the box.

The linked thingiverse files are the ones I used, they are a V1 and required filing to fit correctly.  If requested I can tune these but this was a proof of conecpt project.  A wiring diagram can also be produced upon request, if you are familiar with Arduino / ESP boards you should be able to manage by code review since there are only a couple connections.  Also do take note, there are many versions of the ESP and their pinouts change for many of these different versions, impacting your final wire connections.

Demo:
https://youtu.be/4JEKOjdgWd0

https://gallery.appinventor.mit.edu/?galleryid=566c440a-3d4a-48fe-836f-bf24fb26edf9

https://www.thingiverse.com/miodice3/designs
