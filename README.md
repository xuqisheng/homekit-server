![](https://www.google-analytics.com/__utm.gif?utmwv=4&utmac=UA-92164710-1&utmipc=homekit-server)

# homekit-server
Apple Homekit server for Raspberry PI.

## Video
+ [Youtube](https://youtu.be/rn5vwHkzutk)
+ [优酷](http://v.youku.com/v_show/id_XMTc0NzE3NTc4NA==.html)

## Roles in This Prototype
### Homekit

Apple HomeKit is a framework for communicating with and controlling connected accessories in a user's home. 

### Accessories

Represents a HomeKit device that can be published on your local network.
In this prototype project, both Lamp and Thermometer are accessories.


### Bridge

A kind of Accessory that can host other Accessories "behind" it while only publishing a single device.

The whole project is a Node.js powered Bridge server.

### Lamp

Represents a NodeMCU connected, HSB(hue, saturation and brightness) customizable lamp. See the source code in the examples folder.

### Thermometer Sensor

Represents a WiFi connected sensor. See [my another project](https://github.com/MagicCube/esp-iot-adapter-arduino).

It's built with ESP8266 and DHT11 sensor.
