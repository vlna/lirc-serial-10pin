# lirc-serial-10pin
LIRC hardware for internal serial port

:exclamation: Mainboard serial port header pinout may be different, check with your mainboard documentation.

## Correct serial port pinout

    1 DCD
    5 GND
    7 RTS

### Mainboards with this wiring

Gigabyte EP35-DS3R
Gigabyte Z87-HD3
Zotac NM10-DTX

## Wiring (bottom side)
<- 2x10 pin   1x5 pin ->

    + + + +-+-+
        | |   |
    + +-+ + + +
            |
    + +-+-+-+-+
    
    + + +-+-+ +
              |
    + +-+-+-+-+

## Components (top side)
<- 2x10 pin   1x5 pin ->

    + + R + + +
    + + D I R +
    + + + I + +
    + + + I C +
    + + D C + +

## BOM

    5x6 universal PCB
    2x5 pin 90deg female connector
    1x3 or 1x4 or 1x5 straight or 90deg male connector
    R 4k7
    D 1N4148
    C 4.7uF
    I 78L05
    
    TSOP 1738
    3x1 dupont female-female cable (old CDROM audio cable can be reused)    

## External sources
This module is based on http://www.lirc.org/receivers.html

## License
see [LICENSE](LICENSE)
