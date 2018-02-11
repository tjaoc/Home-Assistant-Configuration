# Home-Assistant-Configuration [![Build Status](https://travis-ci.org/stanvx/Home-Assistant-Configuration.svg?branch=master)](https://travis-ci.org/stanvx/Home-Assistant-Configuration)
[Home Assistant](https://home-assistant.io/) configuration files (YAMLs). These are my Home Assistant configuration files.

# Devices
* [Raspberry Pi 3](http://amzn.to/2nMYhkX) - Hass.io Installed
* [Aeotec Z-Stick Gen5](http://aeotec.com/z-wave-usb-stick)
* [Synology DSM1815+ 8 Bay NAS](http://amzn.to/2ooPHdn)
* [CyberPower CP1300EPFCLCD UPS](https://www.cyberpower.com/vn/en/product/sku/CP1300EPFCLCD)
* [Reolink RLC-422-P IP Camera](http://amzn.to/2n0rHgs) x2
* [Lenovo Tab 4, 8" Android Tablet](http://amzn.to/2vTO7V8) - Used with [HADashboard](https://play.google.com/store/apps/details?id=de.ozerov.fully) and [MQTT Alarm Control Panel](https://play.google.com/store/apps/details?id=com.thanksmister.iot.mqtt.alarmpanel)
* [Xiaomi Roborock Robot Vacuum Cleaner 2](https://xiaomi-mi.com/appliances/xiaomi-mijia-roborock-robot-vacuum-cleaner-2-white) - Robot Vacuum Cleaner
* [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor)
* [Fibaro Relay Switch](https://www.fibaro.com/en/products/switches-2) - Light Switch Control
* [Xiaomi Multifunctional Gateway](https://www.gearbest.com/living-appliances/pp_344667.html) - Gateway used for Xiaomi home automation devices.
* [Xiaomi Window Door Sensors](https://www.gearbest.com/smart-light-bulb/pp_257677.html)
* [Xiaomi Motion Sensors](https://www.gearbest.com/smart-light-bulb/pp_257678.html)
* [Xiaomi Wall Plug](https://www.gearbest.com/living-appliances/pp_344666.html)
* [Xiaomi Wireless Buttons](https://www.gearbest.com/smart-light-bulb/pp_257679.html)
* [Xiaomi Wireless Wall Switch](https://www.gearbest.com/alarm-systems/pp_610095.html)
* [Xiaomi Temperature and Humidity Sensor](https://www.gearbest.com/living-appliances/pp_344665.html)
* [Xiaomi Yeelight RGBW E27](https://www.gearbest.com/smart-lighting/pp_361555.html) - Bedside Lamps
* [Xiaomi Mijia Smart LED Desk Lamp](http://www.gearbest.com/table-lamps/pp_363779.html)
* BroadLink SP Mini 3 x4 - Power Socket Control
* [BroadLink RM Mini 3](https://www.gearbest.com/living-appliances/pp_357329.html) - Projector Room Control
* [Milight WiFi Gateway Emulator](https://github.com/sidoh/esp8266_milight_hub) (NodeMCU ESP8266 / NRF24L01+ module) - Allows for controlling an unlimited amount of LimitlessLED Light groups via MQTT Protocol
* [LimitlessLED Full Color and Dual White Downlight](http://www.limitlessled.com/shop/mr16-rgbw-ww-cw-color-and-white-led) - Smart Dimmable Full Color Downlights
* [LimitlessLED Remote Control](http://www.limitlessled.com/shop/remote-control-for-rgb-ww-cw-color-led-lightbulbs) - Smart Light Remote Control [HASS Integrated](https://github.com/sidoh/esp8266_milight_hub/wiki/Using-Milight-Remote-with-HomeAssistant)
* [Google Home](https://store.google.com/product/google_home) - Voice Assistant/Control
* [Google Home Mini](https://store.google.com/product/google_home_mini) - Voice Assistant/Control
* [Google Chromecast 1](https://www.google.com.au/chromecast/tv/chromecast)
* [Google Chromecast 2](https://www.google.com.au/chromecast/tv/chromecast)
* [Google Chromecast Audio](https://www.google.com.au/intl/en_au/chromecast/audio)
* [Harmony Hub](http://amzn.to/2n0jhG3) - TV and AC Control
* [OwnTracks App](http://owntracks.org) - Mobile Device Tracking
* [Plex Media Server](https://plex.tv) - Media Streaming

# Automations
* Voice Notifications on Google Home's via [Google Assistant Webserver](https://community.home-assistant.io/t/community-hass-io-add-on-google-assistant-webserver-broadcast-messages-without-interrupting-music/37274) on Hassio
* Stream radio stations onto Chromecasts and control their volume.
* On motion from [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor) turn on lights.
* Burgular Alarm from Xiaomi Gateway when alarm panel is Armed and triggered.
* Burgular notifications from [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor)
* Temperature notification from [Fibaro Multisensor](https://www.fibaro.com/en/products/motion-sensor) if no one is home and the home temperature is above 23°C at 5PM. - Option to start the Air Conditioner.
* AC Split System control via [Harmony Hub](http://amzn.to/2n0jhG3).
* Living Room TV Activity control via [Harmony Hub](http://amzn.to/2n0jhG3).
* Daily Automatic Cleaning when nobody is home via [Xiaomi Roborock Robot Vacuum Cleaner 2](https://xiaomi-mi.com/appliances/xiaomi-mijia-roborock-robot-vacuum-cleaner-2-white)
* Change Home Assistant to a dark theme at sunset and back to the light theme at sunrise.
* Hide Media Players from the Home Assistant Default View when not being used.
* IFTTT control of the Office [Xiaomi Mijia Smart LED Desk Lamp](http://www.gearbest.com/table-lamps/pp_363779.html)
* Media Player light control in Living Room, Dim lights when playing and brighten when paused/stopped.
* [LimitlessLED Remote Control](http://www.limitlessled.com/shop/remote-control-for-rgb-ww-cw-color-led-lightbulbs) forwarding to ensure Home Assistant doesn't lose sync whilst using it.
* Turn on Entryway light for 10 minutes once I get home.
* Weather notification at sunrise and sunset.
* Trash and Recycle Bin night reminders - Thanks [CCOSTAN](https://github.com/CCOSTAN/Home-AssistantConfig)!
* Washing Machine monitoring and reminders - Thanks [philhawthorne](https://philhawthorne.com/making-dumb-dishwashers-and-washing-machines-smart-alerts-when-the-dishes-and-clothes-are-cleaned/)!
* UPS status notification (On Battery / Low Battery / On Line)

# Screenshots
#### Day Theme
![Home](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA1.PNG)
![Outside](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA2.PNG)
![Lights](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA3.PNG)
![Other](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HA4.PNG)
#### Night Theme
![Night](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HANIGHT.PNG)
#### HA Floorplan
![HA Floorplan](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HAFLOORPLAN.PNG)
#### HA Dashboard
![Home](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HADashboardHome.jpeg)
![Security](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HADashboardSecurity.jpeg)
![Weather](https://raw.githubusercontent.com/stanvx/Home-Assistant-Configuration/master/screenshots/HADashboardWeather.jpeg)

Configuration files are being edited with Cloud9 IDE [Hass.io Add-on](https://github.com/hassio-addons/addon-ide).

Configuration files are tested against the most stable version of home-assistant using [Travis](https://travis-ci.org/stanvx/Home-Assistant-Configuration).

Message me via the HomeAssistant forums if you have any questions or recommendations in regards to my repository! https://community.home-assistant.io/u/stanvx
