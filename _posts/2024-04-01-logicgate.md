---
title:  "Logic-Gate-Design-and-Verification"
layout: post
---


In this project, I focused on designing and simulating digital logic gates, specifically an Inverter, a 3-input NOR gate (NOR3), and a 3-input NAND gate (NAND3), using a set of electronic design automation (EDA) tools. The overall workflow involved several steps, which are broken down below:

## Schematic Design:
I created the initial schematics of the logic gates using XCircuit, which is a tool for schematic capture. This step defines the logical operation of the circuits at a high level, detailing how the components are interconnected.

## Layout Design and DRC (Design Rule Check):
After the schematic was completed, I moved on to the physical design (layout) using Magic, a layout tool. The layout describes how the components are placed and interconnected on the silicon wafer. During this stage, I also performed Design Rule Checks (DRC) to ensure that the layout met the manufacturing constraints and design rules.

## LVS (Layout vs Schematic) Check:
To verify that the layout matched the original schematic, I used Netgen for a Layout vs Schematic (LVS) check. This step ensures that the physical design aligns with the logical design by comparing the netlist (a representation of circuit connectivity) from the schematic and layout.

## Functional Verification:
Once the layout was verified, I simulated the logical behavior of the gates using IRSIM, a tool for digital logic simulation. This step was essential for confirming that the gates performed their intended logical functions.

## Analog Simulation:
Finally, I analyzed the performance of the gates by conducting analog simulations with Ngspice. This included observing parameters such as signal delay, voltage levels, and power consumption, allowing for a detailed performance evaluation of the circuits.

