# Senior Design
Mosquito Detector and Zapper
This senior design project is supervised by Professor David Westerfeld. The project team consist of three members, two electrical engineers and one computer engineer. This project will utilize skills learned from our classes throughout our engineering programs, circuit design, digital signal processing, programming, etc. The project goal was to create a more effective product than current models in the market. The product was to be able to attract, detect, and eliminate mosquitoes. Current methods of eliminating mosquitoes utilize a bait (typically UV light). Once the target is within the trap, a high voltage electric shock will eliminate anything that makes contact. However, these methods are ineffective towards mosquito population control because the UV bait does not only attract mosquitoes, but other insects as well. Consequently, other insects are also eliminated instead. Our end-product will consist of more advanced methods that will increase chances eliminating our target.

## Built with

* Raspberry Pi
* ADS1015 analog to digital converter
* MAX4466 microphone

## Tested using
* Oscilloscope

## Circuit
![alt text](https://raw.githubusercontent.com/rickyzhangNYC/Senior-Design/master/Images/circuit.png)

## Printed Circuit Board
![alt text](https://raw.githubusercontent.com/rickyzhangNYC/Senior-Design/master/Images/PCB.png)

## Final Design 
The final design uses an omnidirectional electret condenser microphone from UCI Inc. Combined with a Maxim MAX4466 preamplifier to increase the voltage gain and providing high noise tolerance allowing for further processing as shown in figure 1. The signal is first processed with a first order highpass filter and to the ADS1015 analog to digital to converter (ADC). 

