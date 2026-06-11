# mt-spice - SPICE Simulations

A structured repository containing SPICE circuit simulations, schematics, and design verification testbenches for our PCBAs and R&D projects that are not version controlled in Altium.

The goal of this project is to simulate and optimize our A/D circuitry and other R&D projects as well as keeping track for custom/imported models we use across our designs.

---

## 🛠️ Tools & Environment

* **Simulator:** LTspice, TI Pspice
* **Target Hardware:** Custom PCBAs
* **Analysis Types Used:** `.tran` (Transient), `.ac` (Frequency), `.dc` (DC Sweep), `.four` (Fourier)

---

## 📁 Repository Structure

```text
├── models/                 # Custom component libraries, SPICE subcircuits (.lib, .mod)
├── schematics/             # Main schematic capture files (.asc, .sch)
├── netlists/               # Exported SPICE netlists (.cir, .sp)
├── scripts/                # Data post-processing (Python, MATLAB, etc.)
├── .gitignore              # Ignores heavy simulation outputs (.raw, .log)
└── README.md               # You are here!

🚀 Getting Started
1. Prerequisites

Make sure you have LTspice or TI's PSPICE installed on your machine. If you are using any external third-party models, they are bundled inside the models/ directory.

2. Cloning the Repository

bash
git clone https://github.com/[YourUsername]/mt-spice.git
cd mt-spice

3. Running a Simulation

    Open the simulator.

    Navigate to the schematics/ folder and open [Main_Schematic_Name].asc.

    Click Run (or press the running man icon).

    Note: Heavy waveform data (.raw) and simulation logs (.log) are ignored by Git to keep the repo lightweight, so simulations must be run locally to view waveforms.

📊 Key Results & Waveforms

    TBD
