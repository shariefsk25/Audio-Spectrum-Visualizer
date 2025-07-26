Audio Spectrum Visualizer - Multisim Circuit Guide

To build the circuit in NI Multisim:
1. Use an LM741 or UA741 op-amp.
2. Set up the non-inverting amplifier as described.
3. Create three RC band-pass filters:
   - Low Frequency: 10kΩ + 10µF
   - Mid Frequency: 1kΩ + 1µF
   - High Frequency: 100Ω + 0.1µF
4. Each filter output connects through a diode to the base of a 2N2222 transistor.
5. The emitter goes to GND, collector to LED and 330Ω resistor to +9V.
6. Simulate using an AC sine input and ±9V power supply.

For full wiring, refer to the visual block diagram or request the Proteus version.
