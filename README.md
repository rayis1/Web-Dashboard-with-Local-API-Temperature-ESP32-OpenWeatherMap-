Objective:
Measure local temperature using an LM35 sensor and compare it with real-time data from OpenWeatherMap API, displayed on a local web server.

Setup & Tools:

ESP32, LM35 Temperature Sensor

Arduino IDE, WiFi + HTTPClient + ESPAsyncWebServer

OpenWeatherMap API

Summary:
ESP32 reads analog temperature values from the LM35 and fetches external weather data using an API. A built-in asynchronous web server displays both local and API temperature readings on a web page hosted by the ESP32.

