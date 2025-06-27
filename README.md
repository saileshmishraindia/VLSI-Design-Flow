# VLSI-Design-Flow
This Repository will explain all the details wrt VLSI or moreover IC Design Flow . 

The VLSI Design Flow or IC Design Flow refers to the end-to-end process followed to design, verify, and fabricate integrated circuits. It transforms a system-level specification into a functioning silicon chip through a series of well-defined steps. This flow is generally categorized into Front-End Design (logical design) and Back-End Design (physical design). Depending on the methodology, the flow can be Semi-Custom (combining standard logic cells) or Full-Custom (designing everything from transistor level).Broadly there are two types of Design flows : 

- In Semi-Custom Design, the Front-End Flow begins with system specification and architectural definition, followed by RTL coding using hardware description languages like Verilog or VHDL. This is followed by functional verification (simulation, formal methods), logic synthesis (generating gate-level netlists from RTL), and DFT (Design-for-Test) insertion. This flow uses standard cells from a pre-defined library, making it easier and faster for large digital designs like ASICs and SoCs. It prioritizes design productivity and reuse of verified components.

- In contrast, Full-Custom Design focuses on the Back-End Flow, where the designer builds custom transistors, logic gates, and layouts at the transistor level for each function. This gives complete control over device geometry, allowing aggressive optimization for performance, power, and area. The back-end steps include floorplanning, placement, routing, parasitic extraction, clock tree synthesis, and physical verification (DRC/LVS). Full-custom is typically used for analog, RF, high-speed digital, and standard cell library development, where precision and silicon efficiency are critical.

- But When An IC is made or built, It uses two pillars of electronics domain, 1. ANALOG & 2. DIGITAL. Henceforth, There are 2 IC DESIGN FLOWS or IC DESIGN FLOWS (We will use these 2 terms interchangeably, Readers please don't get confused).

![vlsi-design-flow](https://github.com/user-attachments/assets/06771d50-4186-4322-bf75-68ad6d244358)
