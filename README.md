# Sofle v2 Wireless Firmware

## Flash firmware

To flash the firmware, first put your board into bootloader mode by double clicking the
reset button (either on the MCU board itself, or the one that is part of your keyboard).
The controller should appear in your OS as a new USB storage device.

Once this happens, copy the correct UF2 file (e.g. left or right if working on a split),
and paste it onto the root of that USB mass storage device. Once the flash is complete,
the controller should unmount the USB storage, automatically restart and load your newly
flashed firmware. It is recommended that you test your keyboard works over USB first to
rule out hardware issues, before trying to connect to it wirelessly.

## Connecting Split Keyboard Halves

For split keyboards, after flashing each half individually you can connect them together by
resetting them at the same time. Within a few seconds of resetting, both halves
should automatically connect to each other.
