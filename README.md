# PS2toBLE
This is my attempt to bridge a PS2 keyboard to a BLE HID keyboard using an ESP32 based board

## Version 1:

This version simpily glues [This PS2 Library](https://github.com/michalhol/ps2kbdlib) with [this BLE HID sketch](https://gist.github.com/sabas1080/93115fb66e09c9b40e5857a19f3e7787)

Simply plug in a PS2 keyboard (KEYBOARD_DATA 23, KEYBOARD_CLK  22 by default). Annnnd it should all work.

## To Do
1. actually understand HID code
2. figure out how to send keycode (instead of decoding PS2 then encoding it)
3. add macrokeys
4. key mapping