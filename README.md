# rbpi-router

Hello there!

This repository was created for Raspberry Pi router project using D-Link DWM-156 mobile router. 

Firstly, usb_modeswitch library was configured as described here: 
https://askubuntu.com/questions/487004/how-to-add-d-link-dwm-156-to-usb-switch-mode-for-automatic-eject-of-driver-cd

Secondly, wvdial config file under /etc/wvdial.conf was composed as shown in repo.

Please note that 5462 code is only valid for my SIM card. :)

To start internet connection type:

$ sudo wvdial pin

$ sudo wvdial orange
 
Have fun!
