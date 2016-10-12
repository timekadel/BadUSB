# Introduction
BadUSB is a WiFi enabled physical USB Backdoor. Detected as a wireless HID keyboard, the BadUSB will not be detected as a malware of any kind on the host machine. Once plugged on a computer, it launches copies and launches a payload on the distant machine, allowing the ill-intentionned person to have a full R/W access on a terminal in the Host machine. Once pulled out of the machine, no traces of the hack will can be detected by the machine, as the communication happens locally. Meaning that the attacker cannot be identified once an attack is done, in opposition to the use of the couple Metasploit/Payload.

# Prerequisite
In order to create your won copy of the BadUSB, you will need the electronic components listed in the file "Netlist.txt" in the "Electronic" folder and (Sparkfun ain't cheap man... you might want to use another provider) :
1 x ESP8266 Serial WiFi Module (ESP-01) - https://www.sparkfun.com/products/13678<br>
1 x FTDI Breakout board - https://www.sparkfun.com/products/9716 <br>
1 x BadUSB configuration software - In development (coming soon) <br>
1 x STLink V2 programmer - http://www.electrodragon.com/product/st-link-v2-programmer-for-stm8-stm32
