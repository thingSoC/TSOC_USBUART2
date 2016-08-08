# TSOC_USBUART2

The thingSoC USBUART2 Base board incorporates a Cypress CY7C65215 Dual Channel USB Bridge, that supports UART, I2C, SPI, and JTAG interfaces in a thingSoC format.


The thingSoC USBUART2 Base board has two USB bridge channels, which can be programmed to be either UART, I2C, SPI, JTAG, or Capacitance Sensing (buttons/sliders) Human Input devices.

USB Bridge One (Port 1) is connected to an FTDI pinout compatible programming connector, while USB Bridge Two (Port 2) is connected to the thingSoC standard UART channel.

Port1 can be used to program a target microprocessor, at the same time Port2 is used for another purpose (i.e. debug channel, USB to RS-485 bridge, etc).  

It's like having two (2) FTDI adapters in One!

The thingSoC Digital Programming Connector (DPC) is backward compatible with 
the industry standard six (6) pin "FTDI" pinout USB to Serial Adapter pinout.
However, the thingSoC Digital Programming Connector (DPC) includes 
two(2) extra pins (RTS & DEBUG) for extended device programming, 
such as "NodeMCU types" which use the RTS signal as a programming Enable,
and the DTR signal as a programming Reset.


[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/product/TSOC_USBUART2.png?raw=true) 
TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2)

**TSOC_USBUART2** is a Dual USB to UART Base Board **thingSoC Reference Design.** 

**thingSoC Reference Designs** are example thingSoC implementations that implement
various reference and testing circuits for demonstrating the use of the thingSoC libraries.
These reference designs can serve as starting templates for user designs.

---------------------------------------
## Use it as a Programming Dongle

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/product/TSOC_USBUART2_prog_ard_pro.png?raw=true) 
TSOC_USBUART2 to FTDI Six (6) Pin : Programming an Arduino Pro](https://github.com/thingSoC/TSOC_USBUART2)

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/product/TSOC_USBUART2_prog_neoled.png?raw=true) 
Programming a TSOC_NeoLED Board](https://github.com/thingSoC/TSOC_USBUART2)

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/product/TSOC_USBUART2_prog_rs485.png?raw=true) 
Programming a TSOC_RS485 Board](https://github.com/thingSoC/TSOC_USBUART2)

---------------------------------------
## Use it as a Protocol Adapter

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/product/TSOC_USBUART2_adapt_wifi.png?raw=true) 
USB to WiFi Adapter](https://github.com/thingSoC/TSOC_USBUART2)

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/product/TSOC_USBUART2_adapt_rs485.png?raw=true) 
USB to RS-485 Adapter](https://github.com/thingSoC/TSOC_USBUART2)

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/product/TSOC_USBUART2_adapt_rs232.png?raw=true) 
USB to RS-232 Adapter](https://github.com/thingSoC/TSOC_USBUART2)

---------------------------------------
## TSOC_USBUART2 Model Images

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/TSOC_USBUART2_top.png?raw=true) 
TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2)

[![thingSoC TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2/blob/master/TSOC_USBUART2/images/TSOC_USBUART2_bot.png?raw=true) 
TSOC_USBUART2](https://github.com/thingSoC/TSOC_USBUART2)

---------------------------------------

## TSOC_USBUART2 Status <a name="TSOC_USBUART2_status"/>

Revision 1.0 - New Layout with Dual USB to UART device

Revision 2.0 - New PCB Outline, update to thingSoC Revision 2.0 

Revision 4.0 - New DPC connector, fix spacing.

Revision 4.1 - Update silkscreen, add more legends

---------------------------------------

## TSOC_USBUART2 Documentation Index <a name="TSOC_USBUART2_documentation_index"/>

[TSOC_USBUART2 Project](https://github.com/thingSoC/TSOC_USBUART2/)

[TSOC_USBUART2 Hardware](https://github.com/thingSoC/TSOC_USBUART2/tree/master/TSOC_USBUART2/hardware)


---------------------------------------

## thingSoC Documentation Index <a name="thingSoC_documentation_index"/>

[thingSoC Organization Website](http://thingSoC.github.io)

[thingSoC FAQ - Frequently Asked Questions](http://thingsoc.github.io/support/faq.html)

---------------------------------------

[![thingSoC](http://thingsoc.github.io/img/projects/thingSoC/thingSoC_thumb.png?raw=true) 
*thingSoC*](http://thingsoc.github.io)
