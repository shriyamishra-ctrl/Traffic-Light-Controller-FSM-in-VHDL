# Traffic-Light-Controller-FSM-in-VHDL

This project simulates a 2-way traffic light controller (e.g., **North-South (NS)** and **East-West (EW)** directions) using **Moore Finite State Machine (FSM)** in **VHDL**. The design was written, simulated, and verified using [EDA Playground](https://www.edaplayground.com/).

## FSM Description

The system transitions through 4 states with specific timing and output signals for each direction:
| State | NS Light | EW Light | Duration |
|:-----:|:--------:|:--------:|:--------:|
|  S0   |  Green   |   Red    |  10 ns   |
|  S1   |  Yellow  |   Red    |   5 ns   |
|  S2   |   Red    |  Green   |  10 ns   |
|  S3   |   Red    |  Yellow  |   5 ns   |

This cycle repeats to simulate realistic traffic control behavior.


## Features

- **Moore FSM-based** control (outputs depend only on current state)
- **Clocked synchronous design**
- **Testbench** with clock and stimulus generation
- **Waveform visualization** using EPWave on EDA Playground


## Technologies Used

- **VHDL** (IEEE STD_LOGIC_1164)
- **EDA Playground** (GHDL + EPWave)
- **FSM Design** principles
- **Digital logic simulation**

## OUTPUT:

  ![Screenshot 2025-07-07 173445](https://github.com/user-attachments/assets/9604607b-eb0c-4821-bb2c-c44794271fd0)
