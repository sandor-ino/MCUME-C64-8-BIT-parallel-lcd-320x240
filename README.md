# MCUME-C64-8-BIT-parallel-lcd-320x240
MCUME emulator modified to work with a 3.2-inch 8-bit parallel 320x240 LCD

original code: github.com/Jean-MarcHarvengt/MCUME/

Button functions:

left/right/up/down/fire - control joystick, virtual keyboard and start menu.

user 1 - configurable button

key/joy - joystick or virtual keyboard selection

set - in emulation opens setting menu (Joystic port, audio volume, color palette, user function button), in initial menu delete the files in SD, confirm with fire, cancel with set

plus/minus - volume control, used to control parameters in setting menu

reset - reset pico

SD reader integrated LCD display is used. Inside the SD, insert only .PRG files organized into multiple folders, maximum 64 folders and 64 files per folder. Initial menu displays SD contents.

![IMG_4342](https://github.com/user-attachments/assets/048bebeb-d719-4f3f-8421-526b48eb2785)
![IMG_4350](https://github.com/user-attachments/assets/4a342a9d-7391-4c0e-8d39-aad7f20643e1)
![schema picommodore](https://github.com/user-attachments/assets/109283b7-aa46-4dc6-ae60-a74b0671eb3a)
