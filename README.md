# homebridge-fake-rgb

An homebridge plugin that create an Fake RGB Bulb HomeKit accessory

# FORK

this is a fork to control my magichome ledstrip, made for personal use.

# Installation


# Configuration

Remember to configure the plugin in config.json in your home directory inside the .homebridge directory.

```json
"accessories": [{
    "accessory": "Fake-RGB",
    "name": "RGB Bulb",
    "ip": "YOURIPADDRESS"
}]
```

Configuration parameters:

- "accessory": "Fake-RGB",
- "name": "PUT THE NAME OF YOUR TEST BULB HERE",

Look for a sample config in [config.json example](https://github.com/edjopato/homebridge-fake-rgb/blob/master/config-sample.json)
