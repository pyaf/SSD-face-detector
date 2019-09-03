# Face Detection using SSD

This is a web app which uses Single Shot Multibox detector (SSD) framework to detect human faces in a live feed of webcame.


## Demo:


[![Watch the video](templates/index.png)](https://youtu.be/pZFJFl_4o00)

The model is running on CPU, so the response time is a bit slow.


## Requirements

* Pytorch (0.4.1)
* Torchvision (0.2.1)
* Numpy
* Pillow


## Instructions

To run the application:

* Install requirements using `pip installl -r requirements.txt`
* `python app.py`
* Visit `localhost:6006` on your Google Chrome browser.

Note: Please use Google Chrome, this app has some issues running on Firefox.


## References:

The SSD code is adapted form of original open source ssd.pytorch implementation which can be found [here](https://github.com/amdegroot/ssd.pytorch/).

