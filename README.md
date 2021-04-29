# VLIW-Architecture
A Python - Verilog combination that simulates the working of a 32-bit 5-stage pipelined VLIW processor from input assembly code while monitoring the updates in the processor register file.

The VLIW processor contains the following modules:
- Two 32-bit pipelined recursive doubling adders
- One 32-bit pipelined wallace multiplier
- Two 32-bit pipelined floating point adders (IEEE 32-bit floating point representation)
- One 32-bit pipelined floating point multiplier (IEEE 32-bit floating point representation)
- One logic unit
- One memory load unit
- One memory store unit
- One register move unit

Instruction format is given in instructions.txt.

## Demo
- Demo of execution of Test_Cases\demo_1.ss
![Demo of execution of Test_Cases\demo_1.ss](https://github.com/thegamingbot/VLIW-Architecture/blob/main/Demo/demo_1.gif)
- Demo of execution of Test_Cases\demo_2.ss
![Demo of execution of Test_Cases\demo_2.ss](https://github.com/thegamingbot/VLIW-Architecture/blob/main/Demo/demo_2.gif)
- Demo of execution of Test_Cases\demo_3.ss
![Demo of execution of Test_Cases\demo_3.ss](https://github.com/thegamingbot/VLIW-Architecture/blob/main/Demo/demo_3.gif)

## Contributions
| Roll No.  |           Name            |        Email ID        |
| :-------: | :-----------------------: | :--------------------: |
| CED18I044 |  Sai Kaushik Sudhakaran   | ced18i044@iiitdm.ac.in |
| CED18I045 | Samarth Sudarshan Inamdar | ced18i045@iiitdm.ac.in |

## Usage
- For UNIX users
  - ```./setup.sh```
- For Windows users
  - Install Icarus Verilog 
- ```python3 main.py```

## Technologies used
- Python3
- Verilog
