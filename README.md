# READ THIS FIRST

a starter pack for ATS-20 Users

READ THIS FIRST:

THIS IS A W.I.P., EXPECT VISUAL BUG IN BANDNAMES AND MEMORY ISSUES WHILE UPLOADING .

YOU MUST SELECT ONLY ONE MW AND FM BAND (WRITING // AT THE BEGINNING OF THE BAND YOU NOT WANT) THIS FIXES THE BANDNAME ISSUE

PLEASE USE ONLY THE IDE PROVIDED HERE OR YOUR PREFERENCE IDE, NOT ONLINE OR WEB IDE, WEB IDE HAS DETECTED ISSUES.

this pack is intended to be a friendly way to update the firmware to new ATS-20 radio users
this pack offers:

- Arduino IDE v1.8.16 with required libraries included (pu2clr/SI4735, Tiny4kOLED, TinyOLED-Fonts) [although Arduino ide brings required libraries, it is advisable to check the latest version of these in the libraries manager]
- Arduino sketch with dependencies, using PU2CLR and VE3XLT examples
- CH341 Driver required by Chinese Arduino nano clones

the Sketch (v3.0.7g) offers:

- visual changes made by VE3XLT
- battery charge mod by VE3XLT (OPTIONAL)
- band names on screen by VE3XLT
- band table adjustments, filling frequency gaps, fix some visual bugs,fix bat percent bug and improve the step and bandwidth values by CA2PEY
- add the AVC function by PU2CLR

RESET EEPROM (TURN ON + ENCODER PRESSED) WHEN UPLOAD NEW FIRMWARE

INSTRUCTIONS:

- download release
- extract
- install CH341 Driver
- open Arduino ide and update libraries (pu2clr/SI4735, Tiny4kOLED, TinyOLED-Fonts)
- open sketch of you interest (the examples included here [with-without bat mod] or the original included in library -update: this sketch is now in the library exemples-)
- verify and upload
- if a memory issue happens, go to bandtable section and comment (//) the bands that you not use ( pick 1 FM band and 1 MW band )

all other functions in this sketch are the work of PU2CLR

files merged, modified, updated and uploaded by CA2PEY

thanks to PU2CLR and VE3XLT for their work and to all ATS-20 and SI473x enthusiast around the world.

PU2CLR repo https://github.com/pu2clr/SI4735

VE3XLT repo https://github.com/VE3XLT/si4732

Google drive backup https://drive.google.com/file/d/1ZXLXR9YV-TsGLhJIlrseKLT0z55z3gap/view?usp=sharing

ATS-20 Facebook group https://www.facebook.com/groups/allbandradioreceiverusergroup/

all doubt, suggerences and questions here or in the FB group

thanks 73 de CA2PEY
