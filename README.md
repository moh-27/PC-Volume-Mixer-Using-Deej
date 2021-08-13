# DIY PC Volume Mixer - Using Deej 
![IMG_20210813_221647_edit_143262779542721](https://user-images.githubusercontent.com/30930306/129408659-6767c6a7-f634-4a37-b878-5fd1250c1f35.jpg)
![IMG_20210813_221311](https://user-images.githubusercontent.com/30930306/129408940-08190abb-3206-47e6-a371-acd15654da9c.jpg)


This is my take on the [Deej](https://github.com/omriharel/deej) project that allows you to control the volume of any application using circular knobs. This project could be used for Linux and Windows.
Since I don't have accessibility to a 3D printer, I have utilised a box as the body of the audio mixer. My design uses 6 circular knobs, each one controls the volume of a different app and the silver knob for the audio master. 


What is [Deej](https://github.com/omriharel/deej)?
>deej is an open-source hardware volume mixer for Windows and Linux PCs. It lets you use real-life sliders (like a DJ!) to seamlessly control the volumes of different apps (such as your music player, the game you're playing and your voice chat session) without having to stop what you're doing.

This is a brief instruction of the project focusing on the hardware side since the software is explained well within[Deej](https://github.com/omriharel/deej) page.

## Parts
* Box 18x7x9cm
* 6 Potentiometers (WH148 B10K 10K Ohm Linear Potentiometer 15mm Shaft)
* 6 Aluminium Alloy Knob Fit For 6mm Potentiometer Shaft (1 Silver and 5 Black)
* Arduino Nano ATmega328P 
* USB mini to USB cable 
* Wires

## Wiring 
![wiring](https://user-images.githubusercontent.com/30930306/129406209-42e50f0c-8dfb-43f1-8407-525f6b9bd6b6.jpg)

### Potentiometer Wiring
![PotentiometerWiring](https://user-images.githubusercontent.com/30930306/129404840-0b3db6c3-4915-46e8-a538-dfb24b1e9cdd.png)

The potentiometer has 3 pins, the 2 outer pins are for the ground (Gnd) and volts (5V). While the middle pin is the data that is connected to the analog input. 
