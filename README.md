

---

---

# 🧪 Lab Progress – NASSCOM-VSD SoC Design Program

Welcome to the lab progress documentation for the NASSCOM-VSD SoC Design Program. This repository captures each step of the RTL-to-GDS flow using the SkyWater SKY130 open-source PDK and a full suite of open-source EDA tools.

"This program takes learners through the full custom ASIC design flow — from RTL design, synthesis, floorplanning, clock tree synthesis, and routing to physical verification and GDSII generation."

---

## Project Overview

This repository showcases a series of lab sessions that introduce and reinforce the concepts of:

- ASIC flow using open-source tools like OpenLANE, Magic, ngspice, and OpenSTA  
- Digital and analog design concepts  
- Timing closure and physical verification  
- Real-world design techniques using the SKY130 PDK

These labs simulate the full industrial RTL2GDS process — using completely open-source tooling.

---

## Tools & Technologies Used

Tool           | Purpose  
-------------- | -----------------------------------------------  
OpenLANE       | RTL-to-GDSII digital ASIC automation  
Magic VLSI     | Layout viewing, editing, DRC and LVS checks  
ngspice        | SPICE-based circuit simulation  
OpenSTA        | Static Timing Analysis  
TritonRoute    | Detailed and global routing  
TritonCTS      | Clock Tree Synthesis  
SKY130 PDK     | 130nm open-source fabrication process kit  

---

## Labs Summary

Each lab includes screenshots, tool output, and results from different stages of the ASIC flow.

---

**Lab 1: OpenLANE Introduction and RTL Synthesis**  
- Learn OpenLANE structure and setup SKY130  
- Run Yosys for synthesis  
- Simulate and generate netlists
- 

**Lab 2: Floorplanning and Placement**  
- Generate floorplan  
- Define IO pin locations  
- Adjust standard cell density  

**Lab 3: Magic & SKY130 Inverter Design**  
- Design inverter layout using Magic  
- Extract SPICE netlist  
- Simulate VTC and delay with ngspice  

**Lab 4: Clock Tree Synthesis and Timing Analysis**  
- Use OpenSTA for pre- and post-layout timing  
- Insert clock tree with TritonCTS  
- Identify and fix setup/hold violations  

**Lab 5: Routing, Verification, and GDSII Export**  
- Route nets using TritonRoute  
- Run DRC/LVS with Magic  
- Export final layout as GDSII  

---

## ASIC Flow Overview

1. RTL Design (Verilog)  
2. Synthesis with Yosys  
3. Floorplanning  
4. Placement  
5. Clock Tree Synthesis  
6. Routing  
7. Timing Analysis  
8. Physical Verification (DRC/LVS)  
9. GDSII Export

---

## Folder Structure

lab_progress/  
├── Screenshot 2025-03-28 121736.png       (Synthesis results)  
├── Screenshot 2025-03-28 130416.png       (Floorplan view)  
├── Screenshot 2025-03-28 131556.png       (Magic layout)  
├── Screenshot 2025-03-28 135156.png       (Timing output)  
├── Screenshot 2025-03-28 135158.png       (Final GDS)  
└── README.txt or README.md                (This file)

---

## Key Learnings

- Open-source tools are capable of complete RTL2GDS design  
- Pre- and post-layout timing closure is essential  
- Layout design and verification help understand silicon-level constraints  
- A full ASIC design flow is achievable outside traditional industry settings  

---

## Acknowledgements

Thanks to:

- NASSCOM FutureSkills  
- VLSI System Design (VSDOpen)  
- SkyWater Foundry  
- Google’s Open EDA initiative  
- Open-source EDA community  

---

## Related Links

Main Repository:  
https://github.com/pranav007-sys/nassocom-vsd-soc-design-program

This Lab Folder:  
https://github.com/pranav007-sys/nassocom-vsd-soc-design-program/tree/main/lab%20progress

---

"Silicon design isn’t just for foundries anymore. Open-source tools make it real for everyone."

---

