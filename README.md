# 85Programmer

This is a simple arduino shield for using an arduino to quickly program attiny85
microprocessors.

You can do this with an arduino and a breadboard, or you can buy a pre-made USB
programmer. I happened to have everything on hand to build one and I got tired
of using and wiring up a breadboard to do this, so I built this shield.

## Building

Use whatever method you prefer for building the pcb. Along with the Eagle files
I've included a PDF you can print for the toner transfer and photo-resist methods.

You'll need:

* Some pcb and a method to etch or mill it
* 10uF capacitor
* 8 pin dip socket
* pin headers suitable for an arduino shield


## Programming

For this, I assume working with the Arduino IDE. Anything else and you're on
your own.

1. Load the ArduinoISP sketch (File -> Examples) onto your arduino.
2. Set the board to be ATtiny85 (internal 8MHz clock).
3. Set the programmer to be Arduino as ISP
4. Put the shield on the arduino, stick an ATtiny85 into the socket
5. If it's the first time you've programmed the chip, run Burn Bootloader
6. Write your arduino code and upload it as normal.
7. Use your newly programmed ATtiny85!

## License

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

http://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US

## Contributing

Got feedback or fixes? Fork and PR me!
