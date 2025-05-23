# My Home Assistant add-on repository

Add-on documentation: <https://developers.home-assistant.io/docs/add-ons>

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fochorocho%2Fhomeassistant-repository)

## Add-ons

This repository contains the following add-ons

### [Truma Inetbox add-on](https://github.com/ochorocho/homeassistant-inetbox)

This add-on replaces the inetbox using [inetbox.py](https://github.com/danielfett/inetbox.py/blob/master/README.md#inetboxpy).

Once configured, it will send MQTT messages
to the broker. It was tested using the mosquitto Home Assistant Add-on

### [Hetzner DNS add-on](https://github.com/ochorocho/homeassistant-hetzner-dns)

Use the value of a given entity that contains the current external IP address (e.g. UPnP sensor)
and set the IP for a given set of domains using the Hetzner DNS API. 

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
