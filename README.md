# ESPHome Air Quality Sensor
POE Air Quality Sensor based on ESPHome, works with Home Assistant.
Built around WESP32, powered by POE.  Does not support WiFi when wired connection is enabled (but it would be a pretty easy change, even with the same hardware, but in that case there are cheaper non-POE ESP32 boards that could be used).
Computes AQI using PM data.
Radio is used as a bluetooth Proxy (allowing, for example, access to data from nearby Inkbird temperature sensors).

To do: 
- Document required hardware BOM
- Add a gas sensor for CO, Ozone, VOC, etc.

![Components mounted inside "case"](IMAGES/aqi1.jpg)

![Case mounted inside top of bookshelf](IMAGES/aqi2.jpg)
