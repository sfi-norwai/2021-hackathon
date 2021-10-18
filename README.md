# The Robot Car

In this hackathon we're using the [PiCar-X](https://www.sunfounder.com/products/picar-x) robot car.

## Computer
The car is controlled by a Raspberry Pi 4b 8GB.
It runs Raspbian - a specialized ARM version of Debian for Raspberry Pi.

## Sensors
- Camera
- Ultrasonic sensor (forward facing)
- Three grayscale sensors (downward facing in the front)

## Actuators
- Two backwheel servos
- One frontwheel steering servo
- Two camera mount servos (yaw & pitch)
- Speakers

## Batteries
The car is powered by two 18650 batteries.
**Important:
Do not take out the batteries yourself!
When you need new batteries, ask one of the organizers to insert new ones for you.**


# Getting started

## Connecting to the car
The primary way of communicating with the car is through SSH.
Simply turn on the car within reach of the hackathon WiFi and it will read out loud its address, username, and password.
The username is always pi.
You can connect through classical ssh via terminal.
We recommend using [Visual studio Code](https://code.visualstudio.com/) with the [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh) extension.
Then you can get the normal comfort of a development environment (file tree, terminal, code editor, etc.).


## Programming the car
The easiest way to program the car is through Python (feel free to do something else, but without resources from us).
All cars have a script named `test.py` in the home folder (`/home/pi`) that you can run that will test all sensors and actuators.
Run `python3 test.py` to test it out.
Watch out (!) though - the car will start driving.
So make sure to clear a meter or two in front of it or simply hold it in your hands.