# CPU Scheduling Simulator

# Project Overview

This project is a CPU Scheduling Simulator developed using C++. It demonstrates how different CPU scheduling algorithms work in Operating Systems.
The simulaTor takes process details such as:
- Process Name
- Arrival Time
- Service Time (Burst Time)
- Priority (for some algorithms)

and applies various scheduling algorithms to calculate:

- Finish Time
- Turnaround Time
- Normalized Turnaround Time
- Process Execution Timeline

This helps in understanding how the CPU handles multiple processes efficiently.

# Scheduling Algorithms Implemented

### 1. FCFS (First Come First Serve)
Processes are executed in the order they arrive.

### 2. Round Robin (RR)
Each process gets a fixed time quantum for execution.

### 3. SPN (Shortest Process Next)
Process with the shortest burst time gets selected first.

### 4. SRT (Shortest Remaining Time)
Process with the least remaining execution time is selected.

### 5. HRRN (Highest Response Ratio Next)
Process with the highest response ratio gets priority.

### 6. Feedback Queue (FB-1)

### 7. Feedback Queue (FB-2i)
   
### 8. Aging
Used to prevent starvation by gradually increasing priority.

# Technologies Used

- C++
- STL (Standard Template Library)
- Priority Queue
- Queue
- Vectors
- Maps
- Scheduling Logic

# How to Run

### Compile
g++ main.cpp -o main

### Run
./main
For Windows PowerShell:

.\main.exe

# Sample Input

trace
1,3
20
5
A,0,3
B,2,6
C,4,4
D,6,5
E,8,2

# Output Generated

The program displays:
- Process execution timeline
- Waiting periods
- Turnaround Time
- Finish Time
- Normalized Turnaround Time
Symbols used:
* → Running
. → Waiting
  
# Learning Outcome

- Through this project, I learned:
- CPU scheduling concepts in Operating Systems
- Difference between preemptive and non-preemptive scheduling
- Greedy-based scheduling approaches
- Performance comparison between algorithms
- Practical implementation of scheduling logic using C++
