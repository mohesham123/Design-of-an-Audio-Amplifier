# Design-of-an-Audio-Amplifier
The Amplifier is an electronic circuit that is used to increase the strength of a weak input signal in terms of voltage, current, or power. The process of increasing the strength of a weak signal is known as Amplification. One most important constraint during the amplification is that only the magnitude of the signal should increase and there should be no changes in the original signal shape. When a transistor is used as an amplifier, the first step is to choose an appropriate configuration, in which the device is to be used. Then, the transistor should be biased to get the desired Q-point. The signal is applied to the amplifier input and output gain is achieved.
The common emitter amplifier is a three basic single-stage bipolar junction transistor and is used as a voltage amplifier. The input of this amplifier is taken from the base terminal, the output is collected from the collector terminal and the emitter terminal is common for both the terminals.
There are different types of electronic components in the common emitter amplifier which are R1 resistor is used for the forward bias, the R2 resistor is used for the development of bias, the RL resistor is used at the output it is called the load resistance. The RE resistor is used for thermal stability. The C1 capacitor is used to separate the AC signals from the DC biasing voltage and the capacitor is known as the coupling capacitor.
Biasing Circuit/ Voltage Divider
The resistances R1, R2, and RE used to form the voltage biasing and stabilization circuit. The biasing circuit needs to establish a proper operating Qpoint otherwise, a part of the negative half cycle of the signal may be cut-off in the output.
Input Capacitor (C1)
The capacitor C1 is used to couple the signal to the base terminal of the BJT. If it is not there, the signal source resistance, Rs will come across R2, and hence, it will change the bias. C1 allows only the AC signal to flow but isolates the signal source from R2
Emitter Bypass Capacitor (CE)
An Emitter bypass capacitor CE is used parallel with RE to provide a low reactance path to the amplified AC signal. If it is not used, then the amplified AC signal following through RE will cause a voltage drop across it, thereby dropping the output voltage.
Coupling Capacitor (C2)
The coupling capacitor C2 couples one stage of amplification to the next stage.
This technique used to isolate the DC bias settings of the two coupled circuits.
