# FPGA-Driven-Vertical-Transport-Control-System
A compact multi-floor elevator prototype developed using FPGA-based digital control and real-time hardware interfacing.

## About the Project
This project was developed primarily as a learning-oriented exploration into FPGA systems, digital design, and VLSI-related development rather than as a innovation product.

The goal was to gain practical exposure to:
- FPGA-based hardware implementation
- Verilog HDL design
- Finite State Machine (FSM) development
- Real-time control systems
- Motor interfacing
- Hardware-software integration

Through this project, we explored how digital logic can be transformed into a working physical system using FPGA technology.

## System Overview
The prototype simulates a multi-floor elevator system capable of:
- Handling multiple floor requests
- Direction-based elevator movement
- Real-time floor indication
- Physical elevator motion using a stepper motor
- FSM-based control implementation

The control logic is implemented on FPGA hardware and interfaced with external electromechanical components.

## Hardware Used
- Digilent Nexys 4 FPGA Development Board
- Xilinx Artix-7 FPGA Family
- NEMA 17 Stepper Motor
- A4988 Stepper Motor Driver
- Push Buttons
- 7-Segment Display
- Custom Wooden Elevator Prototype

## Technologies Used
- Verilog HDL
- Xilinx Vivado Design Suite
- Finite State Machine (FSM)
- Embedded Hardware Prototyping
- Digital System Design
- Electromechanical System Interfacing

## Development Journey
This was our first FPGA-based project, developed primarily to gain practical exposure to FPGA design, Verilog development, hardware interfacing, and the Vivado design environment. Instead of directly building the final system, we approached the project incrementally through multiple small sub-projects to gradually understand FPGA workflow, debugging, FSM design, peripheral interfacing, and real-time hardware behavior. Starting from basic experiments such as LED blinking and counters, we progressively moved towards motor interfacing and finally developed a complete multi-floor elevator prototype.

Development stages included:
- LED Blinker
- Switch-to-LED Interfacing
- Button Debouncer
- Counter on 7-Segment Display
- Traffic Light FSM
- Up/Down Counter
- Priority Encoder
- Stepper Motor Interfacing with Arduino
- Stepper Motor Interfacing with FPGA
- Mini 2-Floor Elevator Prototype
- Final Multi-Floor Elevator System

This hierarchical approach helped us gradually move from basic digital design concepts to a complete FPGA-based elevator controller system.

## FSM State Diagram

![FSM Diagram](images/fsm_diagram.png)

## Hardware Prototype

![Prototype](images/prototype.jpg)

## Project Highlights
- FPGA-based real-time control implementation
- Physical working elevator prototype
- Multi-floor request handling
- Stepper motor-based motion control
- Practical exposure to hardware debugging and interfacing
- Structured development from basic modules to full system integration

Engineering Design and Innovation,
Department of Electronics & Telecommunication Engineering, 
Vishwakarma Institute of Technology, Pune
