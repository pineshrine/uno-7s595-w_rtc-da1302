
Arduino Uno 7seg digital clock w/ RTC DS1302+ example by pure c language
=====================================

what this project aims to?
========

* no uses arduino language, use just pure c, then I can feel like a /macho/ person
* no uses fancy libraries
* do by your bare-hands!
* then I can learn what's happened down the in the MIKROCOMPUTERS!
* this project is enhancement of previous one <https://github.com/pineshrine/uno-7s595-1>

requirement
--------

* display current time on quad 7-segment led array, such as HH:MM
* blink : on 7-segment led array every second
* time setting by usart console
* time setting by 2 tactile switch
* accurate time within practical uses

miscs
--------

however, this project uses arduino bootloader (I think it's still there), and avr-gcc libraries.

yeah, NIH syndrome is a bad thing mate! follow the UNIX philosophy.

this is just a my hobby project and not intended for actual use anyway.

Design and stuff
========

what's the ingredients?  
--------

* Arduino Uno (ofcource compatible from China one)
* 4 digit 7 segment LED, OSL40391-IG <https://akizukidenshi.com/download/ds/optosupply/OSL40391-XX.PDF>
* 74HC595 x 1
* Resistance 2k ohm x 5, 1k ohm x2 (not armed one)
* 2 tactile switch
* RTC DS1302+ <https://akizukidenshi.com/download/ds/maxim/ds1302.pdf>
* 32.768 kHz XTAL

circuit design
--------

//.. image:: uno-7s595-2.jpg

known issue
========

* unknown

Who's auther?
========

Matsu
twitter @pineshrine<https://twitter.com/pineshrine>

