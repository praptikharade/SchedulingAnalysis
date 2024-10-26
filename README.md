# SchedulingAnalysis
Efficient scheduling plays a crucial role in computer science, as it determines the order of process execution and directly impacts system performance metrics such as turnaround time, waiting time, and response time. Selecting the right algorithms is essential to achieving optimal performance, especially in systems operating under varying loads and priorities.

This project, implemented using Python, compares five fundamental scheduling algorithms:

First-Come, First-Served (FCFS) – Simple and easy to implement but inefficient under heavy workloads due to its non-preemptive nature.
Shortest Job First (SJF) – Minimizes turnaround time but struggles with predicting job lengths.
Priority Scheduling – Adds flexibility by considering task priorities but may starve lower-priority tasks.
Highest Response Ratio Next (HRRN) – Balances fairness and response time by dynamically adjusting priorities.
Earliest Deadline First (EDF) – Effective in real-time systems by executing tasks with the nearest deadline first, but can lead to higher waiting times in non-real-time settings.
This study uses simulation-based evaluations to analyze the performance of these algorithms across different scenarios, focusing on key metrics. The findings provide valuable insights into the strengths and weaknesses of each algorithm, helping practitioners choose the most appropriate strategies for specific applications.
