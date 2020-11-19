
# Readme for Chandy-Misra-Haas Deadlock Detection Algorithm

**---Source Code Files----**

The file names are as follows - 

Chandy-Misra-Haas-OR.cpp

The files are compiled using any online C++ editor or using Visual Studio Code.

**---Execution instructions---**

Execute the code directly from Chandy-Misra-Haas-OR.exe file in your Windows OS.

Enter the number of proccesses --------------input an integer value greater than 1

Enter the wait graph (enter values only 0 and 1)---------enter input values for the wait for graph(see sample) (n x n, n = no of proccesses)

Enter the proccess initiating the probe (between 1 and no. of proccesses)---------input an integer value.

Press Enter to continue
Press q to exit.

----------Sample Test------------ ( please see the demo.png file to more understand)
```
Welcome to Chandy-Misra-Haas Deadlock Detection Algorithm
Press Enter to continue
Press q to quit

Enter the number of proccesses
5

Enter the wait graph
0 0 1 0 0 
1 0 0 1 0
0 1 0 0 1
0 0 0 0 0 
1 0 0 0 0

Enter the proccess initiating the probe
3

Initiating Probe.....

DIRECTION       PROBE
 S3 --> S2     (3,3,2)
 S2 --> S1     (3,2,1)
 S1 --> S3     (3,1,3)
 S2 --> S4     (3,2,4)
 S3 --> S5     (3,3,5)
 S5 --> S1     (3,5,1)
 S1 --> S3     (3,1,3)

        DEADLOCK DETECTED

        Example of OR Model

If want to try again 
Press Enter to continue
Press q to quit
```

- demo wfg
```
0 0 1 0 0 
1 0 0 1 0
0 1 0 0 1
0 0 0 0 0 
1 0 0 0 0
```
- demo1 wfg
```
0 1 1 0 0 0 0
0 0 0 0 1 0 0
0 0 0 0 0 0 1
1 0 0 0 0 0 0
0 0 0 1 0 0 0
0 0 0 0 1 0 0
0 0 0 0 0 0 0
```
- demo2 wfg
```
0 1 1 0 0 0 0
0 0 0 0 1 0 0
0 0 0 0 0 0 1
1 0 0 0 0 0 0
0 0 0 1 0 0 0
0 0 0 0 1 0 0
0 0 0 0 0 1 0
```
- demo 3 wfg
```
0 1 0 0 0 0
0 0 1 0 0 1
0 0 0 1 1 0
0 0 0 0 1 0
0 0 0 0 0 1 
1 0 0 0 0 0
```
