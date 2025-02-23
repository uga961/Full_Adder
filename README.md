# CMOS Full Adder Project

## Overview

This project involves designing, simulating, and analyzing a **CMOS Full Adder** using **Cadence Virtuoso**. The Full Adder is a fundamental combinational circuit used for binary addition, generating a **sum (S)** and a **carry-out (Cout)** output while considering a **carry-in (Cin)** input.

## Software & Tools Used

- **Cadence Virtuoso** (for schematic capture, layout, and simulation)
- **Assura** (for DRC and LVS verification)
- **Analog Design Environment (ADE)** (for waveform analysis)

## Project Workflow

### Schematic Design

- Designed using **Virtuoso Schematic Editor**.
- Constructed using **NAND, NOR, and NOT gates** from a custom-built library.
- Verified through **Transient analysis**.

### Layout Design

- Created using **Virtuoso Layout Editor**.
- Optimized for **area efficiency** and minimal parasitics.
- Design Rule Check (**DRC**) performed for layout validation.

## Technical Specifications

- **Technology Node**: 90nm (as per design constraints)
- **Supply Voltage (VDD)**: 1V
- **Logic Operation**: Full Adder (S = A ⊕ B ⊕ Cin, Cout = AB + BCin + ACin)

## Results & Observations

- **Schematic Simulation**: Verified correct Full Adder functionality.
- **Layout Optimization**: Ensured minimal area and **DRC compliance**.
- **Post-Layout Simulation**: Observed deviations due to parasitic capacitance and resistance.

## Reference Images

- **Full\_Adder\_Schematic**

  ![Full_Adder_Schematic](https://github.com/user-attachments/assets/6806d563-2fb1-49e5-aef9-b5d8f50f48d8)

- **Full\_Adder\_Test**

  ![Full_Adder_Test](https://github.com/user-attachments/assets/8ac97aa5-596a-40a1-804e-ca7acd3a5f49)

- **Full\_Adder\_ADE**

  ![Full_Adder_ADE](https://github.com/user-attachments/assets/1c07d6fd-cea8-4756-b805-967a74cb7e96)


## Caution

- **Note:** For testing, users need to **import the symbol via instance** and check for valid inputs and outputs.

- This project is designed using **custom NAND, NOR, and NOT gates** from a self-built library.

- **Copying this file alone will not work**—users need to **add the NAND, NOR, and NOT gates** to their own library first to use it correctly.

---

*This project belongs to me and is intended for educational and research purposes only. It should not be used directly for other purposes without permission.*

