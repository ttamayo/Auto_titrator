# One peristaltic water pumps set-up

This folder contains in `test.py` that turns on and off a 
peristaltic pump contolled by a power relay.

## Materials:

* Raspberry Pi.
* Power supply.
* Peristalic pump.
* Jumpers.
* Power relay. 

## Set up:

|From: Raspberry   | To: Relay   |
|---|---|
|G17| Input |   
|3V3|3V3 |
|GND|GND |

|From: Power supply   | To: Pump   |
|---|---|
|+|+ |

|From: Power supply   | To: Relay   |
|---|---|
|-|NO |

|From: Pump  | To: Relay   |
|---|---|
|-|COM |

## Notes:

* Please note that the red dot printed on the peristalic pump 
denotes the positive outlet.
