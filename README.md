# 6-Pulse-Converter-using-Simulink  
The basic line commutated converter configuration for HVDC uses a three-phase Graetz bridge rectifier or six-pulse bridge, containing six electronic switches, each connecting one of the three phases to one of the two DC terminals.   
A complete switching element is usually referred to as a valve, irrespective of its construction.  
Normally, two valves in the bridge are conducting at any time: one on the top row and one (from a different phase) on the bottom row.  
The two conducting valves connect two of the three AC phase voltages, in series, to the DC terminals.  
Thus, the DC output voltage at any given instant is given by the series combination of two AC phase voltages.  

During the overlap period, the output DC voltage is lower than it would otherwise be and the overlap period produces a visible notch in the DC voltage.  
An important effect of this is that the mean DC output voltage decreases as the overlap period increases; hence the mean DC voltage falls with increasing DC current
When just valves 1 and 2 are conducting, the DC voltage is formed from two of the three phase voltages.  
During the overlap period the DC voltage is formed from all three phase voltages.
.
The following relation for average DC link voltage are given 
Vdc =  (3√2)/πVLL			------(1)
where VLL= line to line voltage
when firing angle delay is included, the average DC link voltage decreases
Vd=(3√2)/πVLLcosα =1.35VLLcosα-(2)
αis the firing angle and can be varied from 0° to 180°,and thus Vd can be varied from 1.35VLL to 1.35VLL.
If the effect of inductance in ac system is included, Vd average value becomes
Vd=1.35VLLcosα-(3ωL/π)Id
=1.35VLLcosα-RcId
Where Rc= 3ωL/π represents an equivalent resistance to represent the commutation process.
