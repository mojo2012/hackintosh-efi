# hackintosh-efi

This is my current Clover configuration for vanilla macOS 10.15.

No modification of macOS is needed. All the configurations, kexts and efi drivers are in the EFI partition.

Hardware:
* Mainboard: [MSI Z390I-GAMING-EDGE-AC](https://asset.msi.com/pdf/main/de/presale_v2/MPG-Z390I-GAMING-EDGE-AC)
* CPU: Intel Core i3 9100F
* Graphics card: RXFX Radeon RX570 8GB

What works:
* Sound (both HDMI and all other in/outputs)
* Intel itnernal Bluetooth device
* 4k at 60Hz using a DP-to-HDMI 2.0 adapter
* All USB ports (including USB 3.0)
* Eithernet
* Sleep

What doesnot work:
* Graphics cards fans blow at full speed for a few seconds during login screen
* Sometimes kernel panic caused by the eithernet driver
* Integrated WIFI
* Bluetooth Headset microphones

