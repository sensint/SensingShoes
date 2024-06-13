# SensingShoes

Make sure that you have Arduino IDE and Processing ORG installed on your PC. In addition, make sure that "ESP32" library
is added to your Arduino libraries.

Before running the code, make sure that the lights are OFF and the room is dark. Or, cover the shoes from the light!
The time that the light sensors sense light, the microcontrollers start sending data.

1. Open the "Arduino Code" folder and then open the Arduino code named "mainV05.ino" in the "mainV05" folder.
2. Connect the UCB C cable to one of the Tinypico microcontrollers and upload the code.
3. Connect another UCB C cable to the other Tinypico microcontroller and upload the code again.
4. Open the "Processing ORG" folder and open the Processing code named "mainV04.pde" in the folder "mainV04".
5. Run the Processing code and press on the shoes. If you press on (for example) the toe sensor of the right shoe and
the toe sensor of the left shoe changes its color, you need to switch the cables of the Tinypico microcontrollers.

That's it, you have both shoes sending 7 lines of data as following:
Number of loops | Elapsed time | Light sensor data | Sensor_1 | Sensor_2 | Sensor_3 | Sensor_4
