# Xenon

<div align=center><img src="https://github.com/particle-iot/xenon/images/xenon/xenon-top.png" ></div>

### Overview

The Xenon is a low cost mesh-enabled development board that can act as either an endpoint or repeater within a Particle Mesh network.

The Xenon is mesh only and designed to function as the endpoint of your IoT network. It is based on the Nordic nRF52840 and has built-in battery charging circuitry so it’s easy to connect a Li-Po and deploy your local network in minutes.

The Xenon is best for connecting sensors, motors, pumps, valves, and points of data-interest. Pair it with an Argon or Boron gateway to get all that great data into the Device Cloud.


### Features

 * Nordic Semiconductor nRF52840 SoC 
  * ARM Cortex-M4F 32-bit processor @ 64MHz 
  * 1MB flash, 256KB RAM 
  * IEEE 802.15.4-2006: 250 Kbps 
  * Bluetooth 5: 2 Mbps, 1 Mbps, 500 Kbps, 125 Kbps 
  * Supports DSP instructions, HW accelerated Floating Point Unit (FPU) calculations 
  * ARM TrustZone CryptoCell-310 Cryptographic and security module 
  * Up to +8 dBm TX power (down to -20 dBm in 4 dB steps) 
  * NFC-A tag
  * 
 * On-board additional 2MB SPI flash
 * 20 mixed signal GPIO (6 x Analog, 8 x PWM), UART, I2C, SPI
 * Micro USB 2.0 full speed (12 Mbps)
 * Integrated Li-Po charging and battery connector
 * JTAG (SWD) Connector
 * RGB status LED
 * Reset and Mode buttons
 * On-board PCB antenna
 * u.FL connector for external antenna
 * Meets the Adafruit Feather [specification](https://learn.adafruit.com/adafruit-feather/feather-specification) in dimensions and pinout
 * FCC, CE and IC certified
 * RoHS compliant (lead-free)

### Structure of this repository:
 - /eagle
     + Contains the schematic and PCB files in the Eagle file format
 - /gerbers
     + Contains the manufacturing gerber files for the board
 - /datasheets
     + Contains the relevant datasheets of the components used on the Xenon
 - /pdfs
     + Contains schematic files in PDF 

### Hardware datasheet

The complete datasheet for the Xenon is available [here.](https://docs.particle.io/datasheets/mesh/xenon-datasheet/)
