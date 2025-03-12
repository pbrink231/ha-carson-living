# ha-carson-living
[![Coverage Status](https://coveralls.io/repos/github/rado0x54/ha-carson-living/badge.svg?branch=master)](https://coveralls.io/github/rado0x54/ha-carson-living?branch=master)
![Python package](https://github.com/rado0x54/ha-carson-living/workflows/Python%20package/badge.svg)

Custom integration for [Carson Living](https://www.carson.live/) for Home Assistant.

## Disclaimer
Please use this library at your own risk and make sure that you do not violate the
[Terms of Service of Carson](https://www.carson.live/terms).

## Installation

### HACS

Simpliest way to install is using HACS.

Use the button above or go to HACS -> 3 Dots in to right -> Custom repositories

Repository: https://github.com/pbrink231/ha-carson-living

Type: Integration

Move to setup setup below

### Manually

If you want to manually install

Copy files in this repos custom_components/carson/ folder into path/to/haconfig/custom_components/carson/

### Setup

1) Once either HACS or Manually was done (information above)
2) Devices & services
3) Add Integration
4) choose "Carson Living"
5) Login with your Carson Credentials

## Usage

The carson app should create all the door and camera entities available on your carson account.  At this point you can use them as normal.

![image](https://github.com/user-attachments/assets/aed857ac-e09d-4d9d-bb24-8f6bf79e8b79)




