# Klipsch The Sixes – PICkit 3 Connection to Microchip PIC32MX250F128D
---

## WARNING

The high-voltage part of the power supply circuit may be exposed. Do not attempt this unless you have appropriate qualifications.

---

## Hardware Overview

![MCU TOP](images/mcu_board_top.jpg)  
![MCU BOTTOM](images/mcu_board_bottom.jpg)  
![MCU SETUP 1](images/pickit1.jpg)  
![MCU SETUP 2](images/pickit2.jpg)  
![MCU SETUP diagram](images/pickit-connect.jpg)

---

## Power Supply (3.3V)

The MCU is powered directly from a regulated 3.3V laboratory power supply.

Ensure that all unnecessary connections between the MCU and the amplifier board are disconnected. Only essential signal lines should remain (e.g. LED interface, input selector, IR receiver).

High voltage (230V AC) is not required for programming or debugging the MCU via the debugger.

---

![MCU power main](images/pwr1.jpg)  
![MCU power supply](images/pwr2-3V3.jpg)