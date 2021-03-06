# 5 Day Weather Forecast App

A native iOS app to display 5 days weather forecasts. Data via [OpenWeatherMap](http://openweathermap.org/forecast5).

## Install

Requirements:

* An OpenWeatherMap API Key  
* [XCode](https://developer.apple.com/xcode/)  
* [Cocoapods](http://cocoapods.org/)  


1. From the `app` folder, run Cocoapods install:

    ```sh
    $ pod install
    ```

2. Create a Keys.plist file; for example:

    ```sh
    $  cp weather/KeysExample.plist weather/Keys.plist
    ```

3. Open the weather.xcworkspace in XCode; before the first run, **don't forget to edit the Keys.plist file to include your OpenWeatherMap API Key**

## Run/Build/Test

Use XCode to run, build and test the code:

![image](docs/xcode-test.png)

* Choose `Run` to run the app on a Simulator or device;
* Choose `Test` to run the automated tests;
* Select `Product > Build` from the menu to build the app

## TODO

* We have no persistent storage
* There's not much feedback from errors
* The location lat/lon is hardcoded and well hidden in the code
* OMG what is this for an UI
* The app's structure is pretty ad-hoc
* The API includes ways more data than what's presented to the user
* Test coverage is next-to-zero

## License

Lincesed under [The MIT License](http://opensource.org/licenses/MIT) (MIT)

Copyright (c) 2016 Richard Dancsi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
