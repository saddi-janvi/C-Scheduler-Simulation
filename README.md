# C++-Scheduler-Simulation
## Overview
### This programming assignment involves updating a process scheduler simulation in C++. The provided simulation can be found on GitHub: cpu-scheduling-sim. Ensure that you have the g++ compiler installed in your Linux environment.

#### Note: The simulation currently does not account for I/O time, meaning processes switch between Ready and Running without any blocking.

## Task Descriptions
## Task 1: Preemption for PP Algorithm
### Objective: Update the scheduler to implement preemption based on the time quantum for the PP (Preemptive Priority) algorithm.
### Location: Modify the existing source code to enable context switching during preemption.

## Task 2: Allow Same Arrival Time
### Objective: Update the scheduler to allow processes to arrive at the same time.
### Location: Adjust the code to handle simultaneous arrivals of processes.

## Task 3: Implement Preemptive Random Algorithm
### Objective: Add a new scheduling algorithm (PR - Preemptive Random) to the existing set.
### Details: Randomly select a process in the Ready queue to run next, considering the time quantum parameter.

## Building and Running

### Use the provided makefile for easy compilation and rebuilding.
### Execute the simulation with appropriate command-line arguments, such as the algorithm number and time quantum.
