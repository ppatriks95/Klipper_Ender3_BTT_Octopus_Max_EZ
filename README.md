# Klipper_Ender3_BTT_Octopus_Max_EZ

This repository is intended for users migrating to the **BTT Octopus Max EZ** mainboard and setting up **Klipper**.

My configuration is tailored to my personal setup, so **you will likely need to adjust pin mappings and hardware settings** depending on your printer and wiring.

---

## 🔧 My Setup

- **Printer:** Creality Ender 3 (Version 1)
- **Mainboard:** BTT Octopus Max EZ
- **Stepper Drivers:** EZ2209
- **Probe:** BTT MicroProbe V2
- **Camera / Klipper Host:** Samsung Galaxy A13 (OTG Adapter)
- **Klipper Environment:** Beam Klipper

## Pinout how I´ve configured everything
![My Ender 3 + Octopus Max EZ Setup](images/Ender3_BTT_Octopus_Max_EZ_pinout.JPG
)

---

## 📌 Important Notes

⚠️ **This configuration is not plug-and-play.**  
Always verify:
- pin assignments  
- driver configuration  
- probe wiring  
- endstop and heater connections  

Incorrect configuration can cause hardware damage.

---
## 📁 Klipper Firmware
- **Firmware (Octopus Max EZ):**
  
I actually loaded later the Binary file for Klipper from the Developer of Beam Klipper, because my own build wasn´t communicating via Beam Klipper and Klipper itselft. You can get it from [https://github.com/utkabobr/klipper](https://github.com/utkabobr/klipper/releases/tag/prebuilt-v0.12.0)

Specifially I´ve choosed https://github.com/utkabobr/klipper/releases/download/prebuilt-v0.12.0/bigtreetech-octopus-max-ez.bin or you can get it here [bigtreetech-octopus-max-ez.bin](files/bigtreetech-octopus-max-ez.bin)
----

## 📚 Sources / References

All relevant information was gathered from the following official sources:

- **BTT Octopus Max EZ Documentation:**  
  https://github.com/bigtreetech/Octopus-Max-EZ

- **BTT MicroProbe V2 Documentation:**  
  https://github.com/bigtreetech/MicroProbe

- **Beam Klipper Project:**  
  https://github.com/utkabobr/BeamKlipper
