# RFIM_Simulation
2-dimensional Random Field Ising model Monte Carlo Simulation

* __RFIM1.cc__

Simulation with a simple visulization; make sure you have gnuplot installed;
This simulation is very slow because of too many I/O's.

* __RFIM2.cc__

Simulation with only data output.
Two files are exported to folder ".\data". 

=============================================

* __spin_L32_T1.0_r200_sqT.csv__

Spin configurations at different MC steps.
"L32" means system length 32;
"T1.0" means temperature is 1.0;
"r200" means repeat number is 200 (200 repated runs);
"sqT" is arbitrary string you specify when you run the code.

* __MED_L32_T1.0_r200_sqT.csv__

Magnetization, Energy, and Domain wall length at different Monte Carlo steps.
MED means Magnetization, Energy, and Domain wall lenght.
"M" means magnetization;
"E" means energy;
"D" means Domain wall length;
"L32" means system length 32;
"T1.0" means temperature is 1.0;
"r200" means repeat number is 200 (200 repated runs);
"sqT" is arbitrary string you specify when you run the code.
