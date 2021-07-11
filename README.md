# lvgl-Raspberry-pi4
linux demo for raspberry pi 4

Implemented the framebuffer example for raspberry pi4 with 5inch display and touch screen.
There was an bug in the lvgl device driver for touch changed endev_read to return a void.

you can use sudo raspi-config to configure the boot option to 'console automatic logon' and
add vt.global_cursor_default=0 to /boot/cmdline.txt to get rid of the blinking cursor.

last option is to autostart the lvgl application in  /etc/rc.local like su -pi -c yourapp

