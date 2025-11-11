# PLC-Traffic-Light-Program

This project is a **Traffic Light Controller** implemented using **Ladder Logic Programming** on a **Programmable Logic Controller (PLC)**.  
It simulates a real-world 3-color traffic signal system — **Red, Yellow, and Green** — operating in a continuous, timed sequence.

---

## Overview

The project demonstrates the use of **timers**, **logic sequencing**, and **control instructions** in PLC programming.  
It is designed and simulated using the **OpenPLC Editor**, and can be deployed on **Arduino-based PLC hardware** or tested using the **OpenPLC runtime simulator**.

---

## Features

- Sequential cycling of **Red → Green → Yellow → Red**
- Adjustable timer durations for each phase
- Uses **TON (On-Delay Timer)** and **TP (Pulse Timer)** functions
- Ensures **mutual exclusivity** — only one light is ON at any time
- Input switch to start/stop the sequence
- Beginner-friendly for understanding **PLC timing and logic concepts**
- Works with **OpenPLC**, **Arduino**, or any PLC-compatible device

---

## System Configuration

| Component | Description |
|------------|--------------|
| **Software** | OpenPLC Editor |
| **Programming Language** | Ladder Logic (LD) |
| **Target Hardware** | Arduino / PLC-compatible board |
| **Inputs** | Start/Stop switch |
| **Outputs** | Red, Yellow, and Green LEDs |

---

## Ladder Logic Description

- **Timers (TON, TP):** Define the time duration for each signal  
- **Memory Bits (M0, M1, etc.):** Control phase transitions  
- **Logic Flow:**  
