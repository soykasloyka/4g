1. Update Pi and install software
  sudo apt-get update
  sudo apt-get install libqmi-utils udhcpc
  sudo reboot

2. Turn on the SIM7600  module
  sudo qmicli -d /dev/cdc-wdm0 --dms-set-operating-mode='online'

3. Open wwan0 file in the console
  sudo nano /etc/network/interfaces.d/wwan0

4. Copy code from wwa0.conf file from that folder

5. Reboot the Pi
  sudo reboot now
