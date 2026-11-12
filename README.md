# Mini-Digital-Piano

For our final project in Digital Design Lab we decided to make a mini piano using a STM32 microcontroller, switches, an 
amplifier and a speaker. Each switch will correspond to a musical note such that when the switch 
is pressed the speaker will output that frequency note and stop immediately when the switch is 
released. In addition to the basic keys, this mini piano includes a digital volume button, a 
percussion noise button and UART interface will be used to display the volume setting (low, 
medium or high), the note being pressed (C, D, E, F, G or none) and the stage of the note 
envelope (attack, sustain, release).

I did most of the hardware wiring and programmed the frequencies of each note and my lab partner did most of the coding including setting the UART, volume and note envelope. 
