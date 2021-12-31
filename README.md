# Bacterial-optimization
Bacterial Foraging optimization (bio-inspired AI) with an application to Rosenbrock function.
The code is based on Section 2.2 of:


[Chen, Hanning, Yunlong Zhu, and Kunyuan Hu (2009). "Cooperative bacterial foraging optimization." Discrete Dynamics in Nature and Society](https://www.hindawi.com/journals/ddns/2009/815247/)

Currently the BFO code is programmed to optimize the two-variable Rosenbrock function,
f(x,y) = (a-x)^2 + b*(y-x^2)^2
(rose_fungraph plots a countourplot of the Rosenbrock function)

To optimize other functions it is necessary to change fitnessBFO.m
