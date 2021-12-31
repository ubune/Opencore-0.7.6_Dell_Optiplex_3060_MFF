# EFI Opencore 0.7.6 for Dell Optiplex 3060 MFF
I created an EFI based on the Hackintoshlifeit EFI for Dell 3060MFF, with opencore update and some optimisations.

# For Hackintosh users with Dell OptiPlex 3060 MFF.
- You must be on 1.15 Dell 3060 Bios.
- Almost everything is working (even DP/HDMI output) but not DRM (TV App, Netflix on Safari) and microphone line in.
- You must adapt your Platform info (Serial Number, MLB, ROM, UUID) if you want to use Facetime/Imessage.

# Operating system

| Tested On | 
| ------------- |
| Mac Os Monterey 12.1

# Bootloader
| BootLoader | 
| ------------- |
| Opencore 0.7.6 |

# WIFI/BT
Just buy a BCM943602BAED (for example on aliexpress ~60 Euros) and you will have WIFI, BT, Airdrop... and connect :

| Card Connector | Info |
| ------------- | ------------- |
| J0: | white antenna cable (primary wifi) |
| J1: | black antenna cable  (Bluetooth) |
| J2: | Optional Wifi |

Personnaly I adapted the chassis to fix a second wifi Antenna (better WIFI Performance, up to 1300Mbps (~950Mbps in real).

# Hardware Info
| Component | Info |
| ------------- | ------------- |
| CPU  | Intel i5 8500T  |
| iGPU  | Intel® UHD Graphics 630 |
| RAM  | 2x8Go DDR4 2666 MHZ  |
| WIFI/BT  | BCM943602BAED |
| SSD Nvme  | Samsung 970 Evo  |
| SSD Sata | Samsung 860 Evo |
| LAN | RealtekRTL8111 |
| Audio  | Realtek  |
| SMBIOS | MacMini 8,1 |


# Credit
- [Hackintoshlifeit](https://github.com/Hackintoshlifeit) Hackintoshlifeit EFI for Dell 3060MFF.
- [Acidanthera](https://github.com/acidanthera) 
- [Dortania](https://github.com/dortania)
- [WEB] Some discussions, Forum...

