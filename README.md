<!-- omit in toc -->
#  macOS on HP EliteBook 840 G7

<h3> 
    English |
    <a href="">Türkçe</a>
</h3>

<img align="right" src="https://i.loli.net/2021/02/17/KqIEFsp6SjneLTY.png" width="200px" alt="preview">

OpenCore config for Hackintosh OpenCore HP EliteBook 840 G7.

[![macOS](https://img.shields.io/badge/macOS-11.0.1-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.6.6-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/HP-EliteBook-840-G7-Hackintosh/releases)

## Screenshot
<details>
<summary>Big Sur</summary>

![]()

</details>

<!-- omit in toc -->
## Hardware

| **HP** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | HP Elitebook 840 G7      |
| CPU              | Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz (max 4.20Ghz) Comet Lake             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Graphic Card | Intel® UHD Graphics 620                     |
| Wi-Fi             | BCM94360CS2 |
| Sound       | Realtek ALC285                       |

## What are working

- Turbo boost and CPU frequency stage.
- Intel® UHD Graphics 620
  - Brightness control
- Audio Realtek ALC285 
  - layout-id: `11`
  - 3.5mm Combojack
- BCM94360CS2 Wi-Fi and Bluetooth (Airdrop, Handoff..)
- USB 3.0 and Type-C Ports (Port Mapping
- Touchpad (14 gestures are working)
- Battery status
- Camera
- Fn shortcut keys

## What aren't working

- Sleep / Wake
- Built-in Microphone
- Fingerprint
 
With OpenCore Configrator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 16.2
