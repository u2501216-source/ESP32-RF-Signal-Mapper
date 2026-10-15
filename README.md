# ESP32-RF-Signal-Mapper
The RF Signal Mapper is an ESP32-based Wi-Fi monitoring system that scans nearby Wi-Fi networks and measures their signal strength using RSSI (Received Signal Strength Indicator).

The ESP32 displays network information, including signal strength and Wi-Fi channel, on an OLED display. It also provides a web dashboard for viewing detected networks and recording signal measurements. A GPS module can attach location coordinates to measurements when a valid GPS fix is available, while a microSD card can store the collected data for later analysis.

Key Features

*Scans nearby Wi-Fi networks.
*Measures RSSI and identifies Wi-Fi channels.
*Displays network information on an OLED.
*Provides a web-based monitoring dashboard.
*Records signal measurements to a microSD card.
*Supports GPS location tagging when available.

Technologies Used: ESP32, Arduino IDE, C++, Wi-Fi, OLED (SSD1306), GPS, microSD, and HTML/CSS for the web dashboard.

Project Goal: To explore Wi-Fi signal distribution and build a portable system for monitoring and recording wireless signal strength.
