# keybox-model
The repository contains the STL files for the Keybox system
## The software can be found under this [link](https://github.com/theiotproject/keybox-core) 

## Print settings:  
Infill: >= 20%,  
Layer Height: 0.2mm,  
Support: The parts have been designed in a way to not require any supports if you position them correctly.   

## Hardware Required:
- 8x M3 Bolts for every Key Slot (**Disclaimer:** if you decide to use the "Slot Extender" then you are going to need longer bolts to secure the "Hand Blocker" into the Slot)  
- 8x M3 Bolts for both the CTU and ESP32 cover  
- 4x M4 Nuts for a pair of mounters  
- 4x M4 Bolts for a pair of mounters  
  
## Assembly:
You need two pieces of the "Mounter" parts that are located in the "Additional parts" folder for each part to mount in the din rail (with the Button Case being the exception and only the right one is required)  
**IMPORTANT:**  
If your ESP32 is a dev board then you will need to scale down the "Mounters" to atleast 50% in the Z axis as the full sized ones will not allow the wires to fit.  

## Slot Extender?
During testing we've encountered a problem of certain keys *(Car Keys)* not fitting into the Slot properly.  
Thus the simplest solution was to extend space between the slot and hand blocker.  
