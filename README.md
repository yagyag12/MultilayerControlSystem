# MultilayerControlSystemSim

Multilayer (Network + Application) control system simulation on Simulink.

## Overview

This project is a final project for the course *Technologie Informatiche Per L'automazione Industriale* (Information Technologies for Industrial Automation) by Yagiz Yagmur. The project involves a Simulink simulation of an industrial conveyor belt system controlled by a PLC, considering multiple operations, network delays, and physical constraints. A presentation is also included.

## Simulation Subsystems

### Application Layer Only Simulations

- **C + A + P**: Simulates the Controller, Actuator, and Process.
- **C + A + P + S**: Adds Sensor specifications to the simulation.
- **C + A + P + S + D**: Introduces Disturbance to the feedforward.

### Network Layer Only Simulations

- **R + C**: Simulates Input rate (r) and Bandwidth (c).
- **R + C + D**: Adds Disturbance to the network layer.
- **R + C + D + A**: Simulates the effect of attacks on the network, causing the queue to reach the bandwidth limit.

### Multilayer Control Simulations

- **One Process**: Simulation of one process including both the network and application layers.
- **Multiple Processes**: Simulates ten processes simultaneously controlled by the controller with bandwidth distributed based on the needs.


## Usage

- Open the Simulink model, open the subsystem you want to run and run the simulation.
- Adjust the parameters in the model to observe different behaviors and outcomes.

