java c
SYE 4059/ MNE 3204
Homework #2
Please work in groups of two people. Each group will present your solution (5 mins presentation) in class on October 18, 2024. Please upload your presentation slides by 3PM, 18/10/2024.A cantilever I-beam is undergoing a uniformly distributed load (w) and a concentrated force (P) as shown in the figure. The top surface of the beam is instrumented by N (N changes from 2 to 17) strain gauges. Building on materials covered in lectures, find the location of the concentrated force and the magnitude of the distributed and concentrated loads using the sensor data. Write a Matlab or Python script. (or any other coding tool) that takes the data from each sensor set, and output the location,  the  magnitude  of the  concentrated  force  (P)  and  the  magnitude  of  the  uniformly distributed load (w). During the class presentation, you will be given a new set of data to test your code and generate the predictions.Note that we need minimum number of sensors to determine the location and magnitudes, therefore, some data set may not have sufficient information. In this case, please output impossible to solve this problem.Hint: A concentrated force changes the slope of the moment diagram in the beam at the location of the load. If the load is upward, the slope increases and vice versa. Therefore, first try to find where the slope of M(x) diagram makes change. Calculate the values of P and w based on the estimated location of P and the moments of two stain gauges.
<代 写SYE 4059/ MNE 3204 Homework #2Python
代做程序编程语言br>3D view of the cantilever I beam.
Parameter
L (m)
b (mm)
h (mm)
tw (mm)
ts (mm)
E (GPa)
Value
5
100
150
10
20
200
The formula to calculate Moment of Inertia for Bending: 

Sensor data set 1:
Sensor
s1
s2
Location (m)
2.5
5
Strain(mm/m)
0.067409
-0.0735
Sensor data set 2:
Sensor
s1
s2
s3
Location (m)
1.125
2.5
5
Strain(mm/m)
0.028533
0.067409
-0.0735
Sensor data set 3:
Sensor
s1
s2
s3
s4
s5
Location (m)
1
2
3
4
5
Strain(mm/m)
0.022545
0.090179
0.016683
-0.05095
-0.0735
Sensor data set 4:
Sensor
s1
s2
s3
s4
s5
s6
s7
s8
s9
Location (m)
1
1.5
2
2.5
3
3.5
4
4.5
5
Strain(mm/m)
0.022545
0.050726
0.090179
0.067409
0.016683
-0.02277
-0.05095
-0.06786
-0.0735
Sensor data set 5:
Sensor
s1
s2
s3
s4
s5
s6
s7
s8
s9
Location (m)
1
1.25
1.5
1.75
2
2.25
2.5
2.75
3
Strain(mm/m)
0.022545
0.035226
0.050726
0.069043
0.090179
0.096999
0.067409
0.040637
0.016683
Sensor
s10
s11
s12
s13
s14
s15
s16
s17

Location (m)
3.25
3.5
3.75
4
4.25
4.5
4.75
5
Strain(mm/m)
-0.00445
-0.02277
-0.03827
-0.05095
-0.06081
-0.06786
-0.07209
-0.0735



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
