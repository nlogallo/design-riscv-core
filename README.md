# RISC-V Core Design

This repository showcases the design and development of a **RISC-V** CPU core. It is inspired by the **"LFD111x: Building a RISC-V CPU Core"** course by The Linux Foundation on edX.

## Project Overview

This project demonstrates the step-by-step process of constructing a RISC-V core, covering various key aspects of CPU architecture, instruction set design, and implementation techniques. It serves as both a learning resource and a practical example of how RISC-V cores can be built and customized.

## Key Features

Instruction Set Support: Implements core RISC-V instructions including arithmetic, logical, and memory operations.
Branching & Jumping: Full support for branch (e.g., BEQ, BNE) and jump instructions (JAL, JALR), along with proper PC update logic.
Load & Store: Implements load/store instructions, handling byte-addressable memory with word-aligned access.
Immediate Generation: Decoding of various immediate formats (I, S, B, U, J) used across RISC-V instructions.
Pipeline Design: Lays the foundation for potential pipelining stages for instruction fetch, decode, execute, and memory access.

## Learning Source

This project builds upon concepts introduced in the "LFD111x: Building a RISC-V CPU Core" course, which provides an in-depth look at the RISC-V architecture and offers hands-on experience in designing a CPU core from scratch.

## Integrated Development Environment (IDE)

This project utilizes **Makerchip** as the primary IDE. Makerchip is a powerful online platform for designing, simulating, and verifying RISC-V cores and other hardware systems. It provides an interactive environment to develop and test Verilog, SystemVerilog, and other HDL designs directly from your browser.

You can access Makerchip [here](https://www.makerchip.com) to experiment with and run the code from this repository.
