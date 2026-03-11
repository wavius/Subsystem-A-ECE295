# Subsystem A
## Overview
My team was tasked with implementing Subsystem A as part of the ECE295 hardware design course. This subsystem consists of an RX Filter and Quadrature Mixer and is part of the receive chain of the Flexible Radio Transceiver (FLRTRX), the first after the antenna.

## Stages

Antenna ->

Subsystem A
1. Band-pass Filter
    - Third order passive Butterworth filter
2. Low Noise Amplifier (LNA)
    - Cascode common emitter + common base amplifier
3. Quadrature Mixer
    - Gilbert Cell active mixer
4. Low-pass Filter
    - Third order active Sallen-Key filter
5. Amplifier
    - Non-inverting op-amp

-> Subsystem B

## Motivation

The LNA and mixer are discrete implementations because I thought it was more fun and interesting to do it this way. I am pleased with the results and I have become much more comfortable designing and working with transistors.

I was previously quick to rush to the PCB design stage, but now have a lot more appreciation for simulation using spice. I think it is much more important (maybe obviously) to get the functionality right before arranging and routing components, even if the second part can seem more fun and less frustrating.

I had a wonderful experience with the design aspect of the course and would highly recommend others to take a similar discrete design approach.