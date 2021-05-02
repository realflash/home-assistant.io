---
title: Elgato Light
description: Instructions on how to integrate an Elgato Light with Home Assistant.
ha_category:
  - Light
ha_release: 0.104
ha_iot_class: Local Polling
ha_config_flow: true
ha_codeowners:
  - '@frenck'
ha_quality_scale: platinum
ha_domain: elgato
ha_zeroconf: true
ha_platforms:
  - light
---

The [Elgato](https://www.elgato.com/) Lights sets the bar for high-end studio
lightning. The LED lights are created specifically, and designed for streamers
and content creators, many of whom operate on platforms like YouTube and Twitch.

The following light productions from Elgato have been tested with this
integration:

- [Elgato Key Light](https://www.elgato.com/en/key-light)
- [Elgato Key Light Air](https://www.elgato.com/en/key-light-air)
- [Elgato Ring Light](https://www.elgato.com/en/ring-light)
- [Elgato Light Strip](https://www.elgato.com/en/light-strip)

{% include integrations/config_flow.md %}

## Lights

This integration adds the Key Light device as a light in Home Assistant, and
allows you to control the color temperature, brightness, and its on/off state.

When using the Elgato Light Strip, color support is automatically detected
and enabled in Home Assistant.
