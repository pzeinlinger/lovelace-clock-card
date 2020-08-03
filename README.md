# Lovelace Analog Clock Card

A simple analog clock card for Home Assistant. Colors are based on your current theme.

![Example](https://raw.githubusercontent.com/Villhellm/README_images/master/clock-card.png)

| Name | Type | Requirement | Description
| ---- | ---- | ------- | -----------
| type | string | **Required** | "custom:clock-card"
| time_zone | string | **Optional** | The timezone you would like to display. If ommited your current device time will be used.
| size | number | **Optional** | The size of the clock in px. Default is 300
| disable_seconds | boolean | **Optional** | Disable the seconds hand
| show_continent | boolean | **Optional** | Display the timezone continent beneath the clock
| show_city | boolean | **Optional** | Display the timezone city beneath the clock
| caption | name | **Optional** | Caption to display under the clock. This will override both show_city and show_continent

## Example Configuration

```yaml
- type: "custom:clock-card"
  time_zone: "America/Chicago" #OPTIONAL
  size: 250 #OPTIONAL
  disable_seconds: true #OPTIONAL
```

[Troubleshooting](https://github.com/thomasloven/hass-config/wiki/Lovelace-Plugins)