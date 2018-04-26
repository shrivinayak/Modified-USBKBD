Modified version of legacy USBKBD Device Driver.
Driver contains two modes of operations:
Mode1: Normal functioning
Mode2: USB Led indicator shows reverse states for Capslock( on->off off->on )

use Num Lock key to toggle the states.

## Note:
- use make to compile
- use make clean to clean the directory

- load the driver using insmod
- unload the driver using rmmod

