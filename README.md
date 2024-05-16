# Intelligent Cruise Control System Simulation

## Overview

This project simulates the operation of an Intelligent Cruise Control (ICC) system tailored for city road scenarios using MATLAB/Simulink. The ICC system is designed to enhance vehicle control and safety features, particularly for urban driving conditions. It incorporates a control strategy with automatic Stop & Go functionality, ensuring the vehicle follows the lead vehicle while maintaining a safe distance and steady speed.

## Implementation

### Control Strategy

The control strategy implemented in this project involves fuzzy logic-based speed control. The system takes two fuzzy inputs: speed difference (SD) and acceleration (A), and generates a fuzzy output representing throttle control (TC). The fuzzy logic controller operates on predefined rules to determine the appropriate throttle response based on the current speed difference and acceleration.

### Fuzzy Logic Controller

The fuzzy logic controller is designed with seven fuzzy sets for each input: NL, NM, NS, ZE, PS, PM, and PL. These sets represent different levels of speed difference and acceleration. The fuzzy sets are defined using triangular and open left/right membership functions.

### Rules

The system follows a set of predefined rules to map the fuzzy inputs to the fuzzy output. These rules are based on expert knowledge and empirical observations to ensure safe and efficient operation of the ICC system in city road scenarios.

## Usage

To use the simulation:

1. Set the values for speed and acceleration in the provided code.
2. Execute the code in MATLAB/Simulink environment.
3. View the output which represents the throttle control (TC) value.

## Evaluation and Validation

The system's performance is evaluated and validated through simulation findings. Various scenarios are tested to optimize the system's performance in diverse operating conditions. The simulation results are analyzed to ensure that the ICC system effectively follows the lead vehicle while maintaining safety and stability.

## Conclusion

The implemented ICC system demonstrates the feasibility and effectiveness of using fuzzy logic-based control strategies for enhancing vehicle control and safety in city road conditions. Further refinement and optimization can be achieved through continued testing and evaluation in real-world scenarios.
