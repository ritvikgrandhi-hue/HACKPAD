# NINJAPAD
A macropad inspired by Ninjago with a EC11 rotary encoder, 0.91 in OLED display, and a 3x3 matrix of keys. 

##CAD DESIGN:
<img width="1261" height="752" alt="image" src="https://github.com/user-attachments/assets/92de72eb-70df-4c73-8b72-c63c77d5f572" />
The final result of the CAD was an enclosure with 2 layers, where the bottom one holds the PCB in place while the top layer covers everything else. To be able to print the gold/yellow parts, I made each one a separate body to be able to 3D print it effectively. Done in Fusion 360.

##SCHEMATIC:
<img width="1279" height="659" alt="image" src="https://github.com/user-attachments/assets/1bbc1efc-57ef-4132-8e0e-d2856890d066" />
(Sorry for the overlapping labels!) No errors with DRC(for PCB), used a socket symbol for the OLED display and yeah. Done in KiCad.

##PCB:
<img width="761" height="565" alt="image" src="https://github.com/user-attachments/assets/3e2b9844-4648-4b2a-a7a3-a5f4c5e5067f" />
This was the second longest thing to do. It took so many revisions to fix. For example, I accidentally put the parts too close together, then i forgot to add mounting holes, and had to keep it within the 100x100 size limit. Done in KiCad.

##HOW CASE GOES TOGETHER:
<img width="831" height="641" alt="image" src="https://github.com/user-attachments/assets/b3728609-04f3-40db-98a1-27c288de8c84" />
Two plates, glue the gold components on the top plate, put the pcb on the spacers of the bottom plate, and put an M3x16mm screw through it. You'll have to screw directly through the plastic spacers, as I didn't include heatset inserts.

##BOM:
- 1 Seeed XIAO RP2040(with header pins)
- 9x through-hole 1N4148 Diodes
- 9x MX-Style switches
- 1x EC11 Rotary encoders
- 1x 0.91 inch OLED display
- 9x DSA keycaps
- 4x M3x16mm screws
- Case
- PCB
- Soldering iron to put things together
