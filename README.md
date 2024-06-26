# 4 Bit Adder Project

A transistor-level 4 bit adder project, featuring custom designed PCB with SMD components. Designed by myself, with knowledge learned from ECE240 & ECE140 at University of Waterloo


### Demo Video + How I Made It Video

Demo Video: https://youtu.be/0b7SfbxbIe8 <br>
Behind The Scenes (the design & making of this project): https://youtu.be/pEn6NFn74n8

<img src="adder.jpeg" width=500></img>


### What I Used & What I Did
- Prototyped using THT 3904 NPN transistors + LM358 Op-Amp + various resistances (from calculation -> see "calculations" folder, or the video for how I got these values)
- Designed Circuit with Alitum Designer
- Final production is done with SMD equivalences of the above components to save space
- First layer & Control boards are manufactured at home by me, the upper layers are 2-layer PCB's, so I had to order them from a fab
- Soldered using hot air, tested throughly using multimeter & oscilloscope


### Source Files
- The design files (both screenshots & Gerber files) for both first_layer and second_layer are located in the "altium_designs" folder
- The schematics for both layers are in "schematics" folder (first_layer sucks btw, please look at second_layer, I spent way longer to make that one look prettier)
- The calculations behind how I got to the resistance values are in the "calculations" folder (explained in the video)
