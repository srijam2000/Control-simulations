State-Space Analysis & Simulation of Control System:
This repository contains a Python-based simulation for a control system. The project explores State-Space Modeling and compares traditional control techniques with optimal control strategies.

System Overview
The system is modeled as a second-order state-space system using physical parameters (Inertia, Damping, Resistance, and Inductance).

Control Strategies Implemented:
Open Loop: Baseline performance without feedback.
State-Feedback (Pole Placement): Tuning the system response by manually assigning desired closed-loop poles.
LQR (Linear Quadratic Regulator): An optimal control approach that minimizes a cost function to balance performance and control effort.

Performance Analysis
The simulation generates a step response comparison (see Motor Speed Control: Controller Comparison plot) to evaluate:
1. Rise Time: How fast the motor reaches its target.
2. Settling Time: How long it takes to stabilize.
3. Steady-State Error: The difference between the desired and actual speed.

How to Run
Prerequisites
You need Python and the following libraries: pip install numpy matplotlib control
Execution
Simply run the script: python control_sim(1).py
Development Note
This project was developed as part of academics of Intelligent Control Systems. The simulation logic was originally prototyped in Google Colab and refined into a standalone Python script for better modularity.
