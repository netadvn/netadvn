---
title: ASUS DSL-N14U ADSL modem router
keywords: asus asuswrt dsl dsl-n14u n14u modem router
summary: "(Page Status: WIP) Technical Specifications of DSL-N14U"
sidebar: devices_sidebar
permalink: asus-dsl-n14u.html
folder: devices/asus
---

ASUSWRT Firmware for DSL-N14U - Wiki
=========================================

The ASUS DSL-N14U ADSL modem router is a 2-in-1 device with a 300Mbit/s data rate, ASUSWRT user interface and a USB port.

## Device picture

![Asus DSL-N14U](https://www.asus.com/media/global/products/aW4W2PRynAYHOUBk/P_setting_fff_1_90_end_500.png)

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
Type    | ADSL modem router
CPU     | Ralink RT63365E (500 MHz)
CPU Architecture | MIPS 34K (Big Endian) (mips32_r2) (mipsbig) (mips)
Flash/ROM   | Micronix MX25L 16 MB
Memory/RAM  | Etron 64 MB DDR2
Wlan    | Ralink RT5392 802.11 b/g/n
USB     | USB 2.0 x 1
LAN     | 100M / 4 ports
Kernel  | Linux 2.6.22.15
Additional chips | Ralink RT63087N (xdsl)
Power | AC Input: 100-240V (50-60HZ), DC Output: 12 V/1 A

## uname -a
![uname -a](https://camo.githubusercontent.com/acd7b755cca0867e3fc85fccc9f190c906ec0d21/68747470733a2f2f692e696d6779756b6c652e636f6d2f323032302f30332f32312f4a61334a4d6a2e706e67)

## cat /proc/cpuinfo
```
system type             : Ralink RT63365 SOC
processor               : 0
cpu model               : MIPS 34K V5.5
BogoMIPS                : 332.59
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 64
extra interrupt vector  : yes
hardware watchpoint     : yes
ASEs implemented        : mips16 dsp mt
shadow register sets    : 1
VCED exceptions         : not available
VCEI exceptions         : not available
unaligned accesses      : 10788608

processor               : 1
cpu model               : MIPS 34K V5.5
BogoMIPS                : 249.85
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 64
extra interrupt vector  : yes
hardware watchpoint     : yes
ASEs implemented        : mips16 dsp mt
shadow register sets    : 1
VCED exceptions         : not available
VCEI exceptions         : not available
unaligned accesses      : 10788608

processor               : 2
cpu model               : MIPS 34K V5.5
BogoMIPS                : 249.85
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 64
extra interrupt vector  : yes
hardware watchpoint     : yes
ASEs implemented        : mips16 dsp mt
shadow register sets    : 1
VCED exceptions         : not available
VCEI exceptions         : not available
unaligned accesses      : 10788608

processor               : 3
cpu model               : MIPS 34K V5.5
BogoMIPS                : 249.03
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 64
extra interrupt vector  : yes
hardware watchpoint     : yes
ASEs implemented        : mips16 dsp mt
shadow register sets    : 1
VCED exceptions         : not available
VCEI exceptions         : not available
unaligned accesses      : 10788608
```
