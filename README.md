# SonoffControl
Cloned from https://github.com/KmanOz/KmanSonoff

Added ability to choose the BSSID and the Channel when in a multi AP WIFI setup

  `uint8_t bssid[] = {0xXX, 0xXX, 0xXX, 0xXX, 0xXX, 0xXX};`

  `WiFi.begin(WIFI_SSID, WIFI_PASS, 1, bssid);`
