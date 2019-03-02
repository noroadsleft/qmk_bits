# qmk_bits

This repository contains random bits of code and files relevant to [QMK Firmware](https://github.com/qmk/qmk_firmware), but that are not so important that I thought they needed to be in the main repo.

\- noroadsleft  
1 March 2019

noroadsleft (xxiinophobia#5825) on [QMK Discord](https://discord.gg/Uq7gcHh)  

----

## Files

### EEPROM Reset files for Preonic rev3 and Planck rev6

The [`eeprom_reset`](./eeprom_reset) directory contains BIN files for the Preonic rev3 and Planck rev6 that, when flashed, reset the keyboard's EEPROM on startup.

To use them, flash them to your keyboard as normal, then flash your desired firmware file. As these files write to EEPROM on startup and EEPROM has a limited life cycle, these should not be left installed on the keyboard when their functionality is not needed. 

Both keymaps are the default for their respective keyboard; the only differences being the EEPROM Reset operation that occurs on startup.
