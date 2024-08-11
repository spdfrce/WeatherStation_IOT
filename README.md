# WeatherStation_IOT
- A collection of sensors (Soil Moisture Sensor, BM280 Barometric, LDR module, and others) for a correlation and monitoring of maize farm

Log Entry: 7th August 2024
Project Start: 07.08.2024
Time: 🕣

Components Checklist --- To be added
1. Arduino Uno R3 / ESP32
2. Capacitive Soil Moisture sensor
3. BME 280 Humidity/Barometer/Temperature Sensor
4. Raindrop Sensor
5. DHT 11/22 Temperature & Humiditiy Sensor
6. LDR Light intensity module
7. NPK Sensor (To be bought)


Objectives
1. Collect weasther data and soil moisture/nutrient data on a maize farm over a growing period
2. Correlate weather data with the soil moisture/nutrient data
3. Use interpolation techniques to estimte conditions b/n station points
4. Create a visual map of best zones where yield is expected to be high



Future Functionality for the system
1. Weather station transmits data over WAN
2. Two or more stations can connect to each other
3. Farmer can connect to the station network (STA_Net) to view the data from the weather stations locally




##Log Entry##
Time: 21:02

Stages of project
1. Initial Calibration of sensors
   - Capacitive Soil Moisture Sensor ✅

##Log Entry##
Date: 09.08.2024
Time: 03:47

- Testing of a sound threshold sensor
- Purpose: Sensor connected to an RGB LED with common ground
- Upon detection of sound above threshold, a signal is sent to rotate a servo moto at x-degrees
- Currently facing issues with calibrating the sound sensor via the soldered-on potentiometer

##Log Entry##
Date: 11.08.2024
Time: 08:30

Coombining a Real-Time Clock Module with a Micro SD Card
- Purpose is to test a synced entry of texts into a created text file on a 16GB SD card
- Will be implemented to record and timestamp data entry from sensors (Soil Moisture, HumidityxTemp)
- BME 280 (all-in-one barometer x temp x humidity) has had its header pins soldered onto the chip. yet to test.

                  
