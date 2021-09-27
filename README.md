# Unparallel_Weather Station PCB

The Unparallel Weather Station allows anyone to build their own low-cost weather station, using our custom open-source PCB. The software for the weather station is also open-source and can be used as is, or freely customized to meet your own needs and requirements. A model for printing a 3D case for your weather station is also provided.

This Weather Station PCB is a board to simplify the assembly of a weather station using low-cost hardware and a LoPy4 board. The LoPy4 board is equipped with several connectivity options (e.g. Sigfox, LoRa, Wi-Fi and Bluetooth). Currently, the weather station uses Sigfox and/or Wi-Fi to send the data to the cloud, however, the software can be extended to support other connectivity options. A Grafana dashboard is then used to display the historical weather data that is stored on the cloud.

The weather station uses an external sensor (AM2315) for reading temperature and relative humidity, a weather meter kit (SEN-15901) for wind speed, wind direction and precipitation. The weather station is powered from a Li-Ion battery that is charged with a photovoltaic panel which is also used to measure solar radiation. Due to the system’s low-power operation and solar energy harvesting features, it is energy autonomous and can be deployed in remote places.

## Measured parameters:  
*	Temperature (ºC)
*	Relative Humidity (%)
*	Rain (mm/h)
*	Wind Speed (km/h)
*	Wind Gust Speed (km/h)
*	Wind Direction (degrees)
*	Wind Gust Direction (degrees)
*	Solar Radiation (W/m2)
*	Battery Voltage (V)

## Parts list:  
*	Unparallel Weather Station PCB
*	Unparallel Weather Station 3D printed case (optional)
*	AM2315 - Encased I2C Temperature/Humidity Sensor
*	Weather Meter Kit - SEN-15901
*	Li-Ion battery (recommended 3.65V; 8Ah)
*	2.5W Solar Panel (116x160mm)
*	Sigfox antenna (868MHz)
*	LoPy 4.0
