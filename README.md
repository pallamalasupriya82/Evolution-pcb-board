# Custom PCB Evaluation Board Design 📟

A custom-designed embedded evaluation board built to facilitate rapid prototyping and sensor interfacing. Designed from schematic to layout using KiCad.

## 🚀 Overview
This project focuses on the hardware design of a microcontroller development board. It includes power regulation, IO breakout, and necessary peripheral interfaces to test firmware before mass production.

## ⚡ Key Design Features
- **Power Management:** Integrated 5V to 3.3V LDO regulators with reverse polarity protection.
- **Signal Integrity:** Optimized trace routing and ground plane pouring to minimize noise and EMI.
- **Peripheral Access:** All GPIO pins broken out to standard 2.54mm headers for easy breadboarding.
- **Status Indicators:** On-board power LEDs and programmable status LEDs for debugging.

## 🛠️ Tech Stack & Tools
- **EDA Tool:** KiCad (Schematic Capture & PCB Layout)
- **Fabrication:** 2-Layer FR4 Stackup
- **Output:** Gerber Files (RS-274X), BOM (Bill of Materials), Pick & Place file

## 📸 Design Workflow
1. **Component Selection:** Chose components based on availability and datasheet specifications.
2. **Schematic Design:** Created logical connections and defined electrical rules (ERC).
3. **PCB Layout:** Placed components, routed traces, and performed Design Rule Check (DRC).
4. **3D Visualization:** Verified mechanical clearance using KiCad's 3D viewer.
