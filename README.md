# Hackintosh HP 840 G3 Opencore Sequoia
* Opencore EFI for HP 840 G3 running Sequoia

## Changes


## Working
- Full graphics acceleration on Intel HD620 iGPU, including brightness control (F5 and F6)
- Multi-display with DisplayPort OOB, VGA 
- Audio, microphone input and headset output (F8 and F9) - Mute button not working
- GigEthernet LAN connection
- Wireless and bluetooth with any compatible card
- Integrated webcam (OOB)
- CPU power management
- Sleep (Lid, Energy Saver settings, Apple menu, PWR button) & wake (Lid, PWR button)
- Battery management
- Keyboard and touchpad
- Keyboard backlight (F5/F6)
- Touchpad including tap-to-click, scrolling, mouse buttons (can be disable with prt scr key)

![Screenshot](https://github.com/yahgoo/Hackintosh-HP-840-G3-Opencore-Ventura/blob/main/img/macOS%20Ventura%20w%20Apple%20Watch%20Ultra%201600x900.png)

## Not Working
- No Sound. To fix codec

# Specifications:
* CPU: Intel Core i7-6600U
* GPU: Intel HD Graphics HD 520
* Resolution: 1600x900
* Audio: Sunrise Point-LP HD Audio
* Wi-Fi: BCM94360CS2
* Bluetooth: Broadcom Bluetooth 4.0
* Ethernet: Intel
* Touchpad: Synaptics SMBus TouchPad
* Card reader
* Fingerprint: Synaptics Fingerprint Sensors

## Set bios settings as follows:
Advanced tab:  
Boot options:  
- Fast Boot = Disabled
- Network (PXE) Boot = Disabled  
Secure Boot Configuration:
- "Legacy Support Enable and Secure Boot Disable"  
System Options:  
- Virtualization Technology (VTx) = Disabled (recommended, Enable also worked)
- Virtualization Technology for Direct I/O (VTd) = Disabled (recommended, Enable also worked)  
Built-In Device Options:  
- Wake On LAN = Disabled
- Video memory size = 64 MB
- LAN/WLAN Auto Switching = Disabled
- Fingerprint Device = Disabled  
Power Management Options:  
- Extended Idle Power States = Disabled
- Deep sleep = You can keep this enabled
- Wake when Lid is Opened = Enabled
- Wake on USB = Disabled

## Credits 
OSXLatitude - Jake Lo  
ikip
Opencore Dev Team  

