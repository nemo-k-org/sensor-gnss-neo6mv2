# Nemo-K location (GNSS) sensor for NEO 6M breakout board GY-NEO6MV2 

## Overview

This is Nemo-K board for ESP-01 and NEO 6M GNSS breakout board typically labelled
as `GY-NEO6MV2`. The board is widely available in stores selling Arduino-IoT related stuff.

The board sends GNSS information to Signal K server.

The board is designed to be used with ESP-01 microcontroller running Nemo-K firmware.

To build you need
 * The PCB
 * ESP-01S
 * NEO 6M GNSS breakout board
 * Four plastic hexagon motherboard spacers (length 8 mm, thread M2.5)
 * Eight M2.5 screws (length max 4 mm)
 * For external GPS antenna: pigtail from [Hirose U.FL](https://en.wikipedia.org/wiki/Hirose_U.FL) to typically
   SMA male/female

## Content

The repository contains schematics and PCB in KiCad 8.0 format. The footprint properties contains LCSC part numbers
used by [JLCPBC.com](https://jlcpcb.com). If present, the `sensor-gnssneo6mv2/production/` contains all necessary
files to order boards from JLCPCB. The production files can be easily re-created using
[KiCad Fabrication Toolkit](https://github.com/bennymeg/Fabrication-Toolkit).

The Nemo-K project is not affiliated or sponsored by JLCPCB. The project does not endorse JLCPCB.

## Changelog

2025-11-15 v3 - Revised after 1st proto
 * Changed power connector footprint to LCSC C5349550
 * Adjusted holes with GPS breakout board
 * Added test pads for voltage

2025-10-26 v2 - First prototype
 * First prototype was sent to production

## Copyright and License

The license and copyright can be found in the file `LICENSE`.

The license and copyright cover only the schematic diagram and the PCB design. It does not cover footprints and other
embedded elements or technical documentation which may or may not be covered by their own licenses.
