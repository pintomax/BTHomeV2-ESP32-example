# BTHomeV2 ESP32 Example
# V2 of the example, simplified for least input
An example BTHome v2 example with a presence and a count sensor
Thanks [@countrysideboy](https://github.com/countrysideboy) for his contributions on Encryption and cleanup code, the most of the code is from his side!

# Notice it's currently under development

This is an example for a DIY [BTHome v2](https://bthome.io/) sensor.

The original code is from: https://github.com/TheDigital1/ESP32_BTHome

The header file contains human readable variables for the hex Object ids.

Sending entities to Home Assistant is simplified.

1) Download the files from Arduino Code folder.

2) Edit the BTHome.ino in your favourite Arduino IDE 

3) Change the DEVICE_NAME to the one that should be recognised in BTHome integration

4) Add the object id of the individual entities and the state of it as in the examples

5) Compile and upload to ESP32

DONE!

# Encryption is enabled on default, can be disabled by removing the `#define ENABLE_ENCRYPT` line
# Default encryption key (Bind_Key): 231d39c1d7cc1ab1aee224cd096db932 (Please change it for secutity reasons - Should be a 32 digit hex)

Read the comments in the code for more info. 
For the object ids consider using the variables from BTHome.h instead.
