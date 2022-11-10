# install openCV (?)
Full package installation: `pip install opencv-contrib-python`

open python3 terminal
```
import cv2
cv2.__version__ <-- should print '4.6.0'
```

# Running Code on Raspberry Pi
On Rasberry Pi with the very nice broken screen: 
1. Start hotspot 
2. Run ```sudo raspi-config``` in terminal
3. Connect to hotspot
4. Type ```hostname -I``` in terminal for IP Address 
    * Kathleen Hotspot: 172.20.10.6

On your own computer
1. Join hotspot
2. Type ```shh saaniya@IP_ADDRESS```
    * First time running: type ```yes```
3. Enter password
4. Edit a file: ```sudo nano file.py```
    * ```control x``` to save
    * ```control k``` for faster deleting (actually cutting on line at a time but it works)
5. Run a file: ```sudo python file.py```