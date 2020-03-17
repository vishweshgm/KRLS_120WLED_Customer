# KRLS_120WLED_Customer

[![N|Solid](http://qpowersys.com/Images/qps_final-01.png)](https://nodesource.com/products/nsolid)

[![N|Solid](http://www.krlightingsystems.com/images/logo.png)](https://nodesource.com/products/nsolid)

# V1.1.0 Release: New Features!
- FLK text changed as SPE

# V1.0.0 Release:New Features!

- Added logic : To set intensity & cct to 0 & 5800 respectively if eeprom erased after flash program.
- Changed logic : Unit after power on jumps to normal mode instead of standby every time.
-  Changed Logic : For Patterns - lightning, tubelights, welding minimum required intensity set to 50%. If these patterns enabled below 50% unit will automatically upgrade intensity to 50 and starts the flickering.
- InternalUpdate: PWM function now will be called only if there is a change.(saves CPU Load)
- Internal Update: Updated ADDR_FLASH_PAGE_60 as eeprom instaed of page 48 to compensate for increased ROM size.


