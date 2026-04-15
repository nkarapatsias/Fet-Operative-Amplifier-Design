# FET Operational Amplifier Design

## Overview
This repository contains the design and verification of a custom operational amplifier built entirely with MOSFET transistors. Originally developed as a university project, the amplifier was fully designed, simulated, and tested using **Cadence Virtuoso**.

The primary objective of this project was to build an amplifier that strictly adheres to specific analog performance constraints, balancing gain, bandwidth, and power consumption. **All design requirements were successfully met.**

## Tools Used
This project was developed and verified using industry-standard analog IC design tools:
* **Schematic Capture & Layout:** Cadence Virtuoso
* **Simulation & Verification:** Analog Design Environment (ADE) / Spectre
* *(Note: Ensure you have the appropriate Cadence licenses and the correct university PDK sourced in your environment before opening the project).*

## Design Specifications
The target specifications for the operational amplifier, which have all been achieved and verified via simulation, are outlined below:

* **DC Gain (A0):** >= 30 dB
* **Bandwidth (BW):** >= 500 kHz
* **Phase Margin (PM):** >= 45°
* **Supply Current (Isup):** <= 50 µA
* **Offset Voltage (Voffset):** < 20 mV
* **Slew Rate (SR):** >= 1 V/µs
