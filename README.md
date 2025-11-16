# SIDHARTHAN-V
DC-Position-Control-System
Aim:
To control the position of motor having the following specifications using MATLAB.
(J) moment of inertia of the rotor = 3.2284E-6 kg.m^2
(b) motor viscous friction constant = 3.5077E-6 N.m.s
(Ktf) motor torque constant = 0.0274 N.m/Amp
(R) electric resistance = 4 Ohm
(L) electric inductance = 2.75E-6H

Apparatus Required:
Computer with MATLAB software

Theory:
The speed of a DC motor is directly proportional to armature voltage and inversely proportional to flux. In field controlled DC motor the armature voltage is kept constant and the speed is varied by varying the flux of the machine. Since flux is directly proportional to field current, the flux is varied by varying field current.

The speed control system is an electro-mechanical control system. The electrical system consists of armature and field circuit but for analysis purpose, only field circuit is considered because the armature is excited by a constant voltage. The mechanical system consists of the rotating part of the motor and the load connected to the shaft of the motor. The field controlled DC motor speed control system is shown in the below figure. For this field controlled DC motor we shall find transfer function.

image
Let Rf = Field resistance
Lf = Field inductance
if = Field current
Vf= Field voltage
T = Torque developed by motor
Ktf = Torque constant
J = Moment of inertia of rotor and load
The equivalent circuit of field is shown in the below figure.
image

By Kirchoff ‘s voltage law, we can write
image
The torque of DC motor is proportional to product of flux and armature current. Since armature current is constant in this system, the torque is proportional to flux alone, but flux is proportional to field current.

                                            T ∝ if 

                                    Torque , T = Ktf if
The mechanical system of the motor is shown in the below figure.
image

The differential equation governing the mechanical system of the motor is given by,

image

On taking Laplace transform of the above equations with zero initial condition we get,
image
Equating equations (2) & (3) we get,
image
The equation (1) can be written as
image
image

Procedure:
Open MATLAB software
Open a new script file.
Type the program.
Save and Execute the program.
Analyse the output in open loop and closed loop.
Program
Output
Result
Thus, the position of dc motor is controlled using MATLAB.
