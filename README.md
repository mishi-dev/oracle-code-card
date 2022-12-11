# oracle-code-card


To configure a Wi-Fi connection for an ESP-12F module using the Arduino IDE, you can follow these steps:

Install the Arduino IDE on your computer and connect the ESP-12F module to your computer using a micro-USB cable.

Open the Arduino IDE and go to File > Preferences. In the "Additional Boards Manager URLs" field, add the URL for the ESP8266 Arduino Core: http://arduino.esp8266.com/stable/package_esp8266com_index.json

Go to Tools > Board > Boards Manager and search for "esp8266". Install the latest version of the ESP8266 Arduino Core.

Go to Tools > Board and select "NodeMCU 1.0 (ESP-12E Module)". This will set the ESP-12F module as the active board in the Arduino IDE.

In the Arduino IDE, go to File > Examples > ESP8266WiFi and open the "WiFiClient" example.

In the code, update the ssid and password variables with the name and password of your Wi-Fi network.

Click the "Upload" button to compile and upload the code to the ESP-12F module.

Once the code is uploaded, open the serial monitor by going to Tools > Serial Monitor. The ESP-12F module should connect to your Wi-Fi network and display the IP address it has been assigned.

You can now use this IP address to access the module and control it over your Wi-Fi network.
