# MagSafe e-ink reader (ESP32-S3)

A phone-mounted e-book reader, currently in the design phase. The idea is an ESP32-S3
driving a 3.7" SPI e-paper display, reading books from a microSD card, powered by a LiPo battery.

## Status
- Enclosure: designed in Fusion 360 (STL and 3MF files in `cad/`)
- Parts: selected, not yet ordered
- Firmware (C++): planned

## Selected hardware
ESP32-S3 (XIAO), 3.7" SPI e-paper display, microSD card, LiPo battery,
vibration motor (driven by a 2N2222 transistor), capacitive buttons (copper tape)

## Files
- `cad/`: enclosure design (STL, 3MF with OrcaSlicer settings)