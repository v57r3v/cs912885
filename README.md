java c
ECE 141, Winter 2025
Homework 4
Due Feb 11, 2025 at 11:59pm


Problem 1. Consider a control system represented by the transfer function in (1). Let y denote the output Y in time domain, and u denote U. Then, take x1 = y and x2 = ˙x1, and write the state-space representation of G where x1 is your first state, and x2 is second.





Problem 2. For the system in Fig. 1, where   






(a) Determine the transfer function from R(s) to Y (s), assuming W(s) = 0. Find the nominal steady-state tracking error ER(s) := R(s) − YR(s) = [1 −R/Y(s)]R(s) with:
(i) a unit-step reference input;
(ii) a unit-ramp reference input.
(b) Determine the transfer function from W(s) to Y (s), assuming R(s) = 0. Find the disturbance steady-state tracking error EW (s) := R(s)−YW (s) = −W/Y(s)W(s) with:
(i) a unit-step disturbance input;
(ii) a unit-ramp disturbance input.
(c) Now, assume neither W(s) nor R(s) is zero. Express the overall output Y (s) := YR(s)+YW (s) as the weighted sum of inputs R(s) and W(s). Then compute the overall steady-state tracking error E(s) := ER(s) + EW (s) with both:
(i) a unit-step reference input AND unit-step disturbance;
(ii) a unit-ramp reference input AND unit-ramp disturbance.
Problem 3. Block diagram representation for a magnetic tape-drive system is sho代 写ECE 141, Winter 2025 Homework 4Matlab
代做程序编程语言wn in Fig. 2, and note that J and b are given at the bottom left corner of the figure.
(a) Assuming the reference is zero, what is the disturbance steady-state track-ing error due to a step disturbance torque of 10 N·m? What must the amplifier gain K be in order to make the disturbance steady-state track-ing error edss ≤ 0.05 rad/sec?



Figure 1: Block diagram representation of the system for Problem 2
(b) Plot the roots of the closed-loop system in the complex plane. Sketch the time response of the output for a step reference input, assuming no disturbance present, using the gain K computed in part (a);
(c) Plot the region in the complex plane of acceptable closed-loop poles cor-responding to the specifications of a 1% settling time of ts ≤ 0.05 sec and an overshoot Mp ≤ 1%;
(d) Replace the amplifier K with a PD controller. Give values for kP and kD which will meet the specifications in (c), assuming no disturbance;
(e) How would the disturbance steady-state tracking error change with the new control scheme in part (d)?
(f) How could the disturbance steady-state error be eliminated entirely?

Figure 2: Block diagram representation of the system for Problem 3




Bonus 1. Verify your answers to Problem 3 using Matlab.









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
