#Internet Controlled Wireless Relay

Going to attempt to make a IoT device. Going to see if I can use the Pro Mini and 2x NRF24L01 transceivers to make a wall outlet controlled via a R Pi from anywhere, over the internet.  

The plan is to use the Pi to handle the internet side, probably running a websever. This way I could create a page with a button. Click the 'On' button and the page fires off a script that sends an 'on' signal via the NRF24L01 to the another NRF24L01 connected to a Pro Mini. Which then actuates the relay. Off button will do the same thing turning off the switch.

Maybe I can eventually swap the Pro mini for something smaller like a ATTiny.

Uses
* Pro Mini Atmega328 5v 16m
* NRF24L01 Wireless Transceiver
* Couple of 3-5v relays
* Raspberry Pi (any model)
* Power outlet
* Light switch (manual off switch)
* Case and face plate to hold outlet and power switch. Big enough to hold the relays and Pro Mini as well.

