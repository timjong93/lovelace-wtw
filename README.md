# Homeassistant Lovelace WTW card

Use https://github.com/LukasdeBoer/esp8266-whr930-mqtt to connect to your WHR930 and then use this lovelace card to visualize your data!

# Installation

* Clone this repo into your `www` folder inside your configuration. So it will be: `config_folder/www/lovelace-wtw`. 
* Edit your lovelace-ui.yaml or use the flat configuration mode in lovelace and add to the top:
```
resources:
  - type: module
    url: /local/lovelace-wtw/wtw-cards.js
```
* Add a card with `type: 'custom:wtw-card'` to your UI.
* Restart home assistant
* ???
* Profit!