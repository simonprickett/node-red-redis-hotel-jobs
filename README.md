# Redis Hotel Jobs Example with Node-RED for Raspberry Pi

Redis backed hotel jobs example using node-red.

![The Node-RED Flow running on a Raspberry Pi](redis_node_red_flow_pi.png)

## Videos

Watch the two livestreams that I did covering this project...

* [Episode 1](https://www.youtube.com/watch?v=byt8jWg6M98) (YouTube)
* [Episode 2](https://www.youtube.com/watch?v=r3yaVFN7Mzg) (YouTube)

## Prerequisites

This project can run on a Raspberry Pi or any other computer that can run Node-RED.  If you're using a Raspberry Pi you can optionally get the LED/arcade button and wires and use those too.  If you don't have these or aren't running on a Pi, the alternative Node-RED flow (see later) doesn't require these.

* A [Raspberry Pi](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/) (model 3B or 4) or any other computer that can run Node-RED
* An up to date version of [Node.js](https://nodejs.org/) - pick the latest LTS version (if you're on a Raspberry Pi, the Node-RED install script will take care of this for you)
* [Node-RED](https://nodered.org/)
* A 24mm illuminated arcade button (blue - note red or green options won't work as these need 5v and the Pi uses 3.3v).  [UK supplier](https://thepihut.com/products/mini-led-arcade-button-24mm-translucent-blue) | [USA supplier](https://www.adafruit.com/product/3432)
* Arcade button quick wires (10 pack - you only need 2, other wiring options work too but may involve soldering). [UK supplier](https://thepihut.com/products/arcade-button-quick-connect-wire-pairs-0-11-10-pack) | [USA Supplier](https://www.adafruit.com/product/1152)

## Node-RED Setup

TODO

## Node-RED Flows

This repository contains two versions of the same Node-RED flow as follows:

* `flows_no_hardware.json` - use this if you're not using the optional arcade button and LED, and/or if you aren't running Node-RED on a Raspberry Pi.
* `flows_with_hardware.json` - use this if you're running on a Raspberry Pi and have fitted the optional arcade button and LED.

## Hardware Setup

TODO