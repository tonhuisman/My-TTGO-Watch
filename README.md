# My-TTGO-Watch

A smartwatch based on ESP32 from LlyGo. Currently under development.

# Install

Clone this repository and open it with platformIO. Build and upload. On a terminal in vscode you can do it with

```bash
pio run -t upload
```

or simple press "build and upload" in platformIO.

# how to use

On startup you see the main screen (time tile). It show the time and the current weather (if correct configure). Now you can swipe with you fingers up, down, left and right between the four main screens. The four screens are organized in time, apps, note and setup tile.
For the weather app you need an openweather.com api-id. http://openweathermap.org/appid is a good starting point.

# how to make a screenshot
The firmware has an integrated webserver. Over this a screenshot can be triggered. The image has the format RGB565 and can be read with gimp. From bash it look like this
```bash
wget x.x.x.x/shot ; wget x.x.x.x/screen.565
```

# Interface

![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen1.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen2.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen3.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen4.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen5.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen6.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen7.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen8.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen9.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen10.png)
![screenshot](https://github.com/sharandac/My-TTGO-Watch/blob/master/images/screen11.png)
