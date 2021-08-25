# Hackintosh-Dell-G3-3500
Catalina running (somewhat) on i5 Dell G3

## Machine specs
- **CPU** Intel Core i5-10300H 2.5 GHz Quad Core
- **RAM** 16 GB DDR4 2933 MHz (2 x 8GB)
- **iGPU** Intel UHD 630
- **dGPU** Nvidia GTX 1660 6 GB
- **SSD** 512 GB NVMe
- **Display** 15" 1920 x 1080 60 Hz
- **Sound** Realtek ALC 295
- **Ethernet** Killer E2500 2.5 Gbps (Realtek RTL8111 chipset)
- **Thunderbolt** Intel Thunderbolt 3
- **WiFi** Intel AX 201
- **Bluetooth** Intel (combined with wifi)
- **USB** 2x USB2, 1x USB3 Type A, 1x USB3 Type C (Thunderbolt)
- **Other** Webcam, SD card reader, backlit keyboard...

## Working
- CPU power management
- iGPU
- Ethernet
- Brightness adjustment
- Internal card reader
- Webcam
- Sound
- Wifi
- USB
- Touchpad
- iServices (Generate unique serial first!)

## Not working
- dGPU (Nvidia probably never will)
- Sleep/wake
- Internal microphone
- Thunderbolt
- USB-C port that is shared with the Thunderbolt port
- If you insert a USB hub into a USB 2.0 port, the other 2.0 port briefly disconnects and then reconnects again. (Mainly an issue with flash drives)
  - This is not an issue with the USB 3.0 port on the left
- WiFi is 20 MHz channel width only, which limits the bandwidth to around 144 Mbps
- Touchpad always registers a force touch (which can be disabled in System Preferences but annoying)

## Untested
- 2.5 Gbps ethernet (I don't have another 2.5 gig device. 1 Gbps works.)
- HDMI port
- DisplayPort

## Credits
Heavily based on the config.plist at https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579 
