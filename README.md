# 2.0" TFT LCD 240×320 – EDA Files

Fusion 360 and STEP files for the common **2.0-inch ST7789 240×320 IPS TFT** with 12-pin FPC. The one you see everywhere on Aliexpress for $4-6).

<img width="1512" height="982" alt="Screenshot 2026-04-21 at 2 01 51 PM" src="https://github.com/user-attachments/assets/c3520eeb-daf9-418e-9208-057081ee612c" />


## Why this exists

These 2 inch LCD displays are common on Aliexpress but I find the Module boards to be too bulky. I designed a basic Fusion 360 footprint based on the LCD panels datasheet so you can design the LCD straight into your PCB as a design reference. To be used with a 12 pin FPC connector.

This is the 12-pin SPI version (not the 20-pin parallel one), typically with ST7789V or ST7789VW driver.

## Specs

- **Size:** 2.0" diagonal
- **Resolution:** 240 × 320 (RGB, portrait)
- **Driver:** ST7789V / ST7789VW (some batches use ILI9341 – same pinout)
- **Interface:** 4-wire SPI + D/C, RST, CS, BL
- **Pins:** 12-pin FPC, 0.5mm pitch
- **Module size:** 35.0 × 50.8 × 2.2 mm (measured)
- **Active area:** 30.6 × 40.8 mm
- **Voltage:** 2.8–3.3V logic, 2.8V typical for LED backlight
- **Viewing:** IPS, all angles

## What's in this repo
