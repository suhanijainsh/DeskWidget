This project is a real-time flight tracking system built on the ESP32-C3, using a 1.3" SH1106 OLED display and a touch-based interface. It connects to WiFi using WiFiManager and retrieves live aircraft data from the OpenSky Network API. The device processes nearby flights, calculates their distance from a fixed location using the Haversine formula, and displays key information such as callsign, distance, and altitude.

The system also includes a secondary image display mode that renders preloaded bitmaps on the OLED. A single touch sensor is used for interaction, allowing users to switch between modes with a long press and cycle through images or flights with a short tap. The interface is designed to be responsive and efficient, using non-blocking timing and simple animations for smoother data updates.

Overall, the project combines embedded systems, API integration, and lightweight UI design to create a compact and interactive aviation display device.
