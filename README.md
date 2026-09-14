# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**


<img width="900" height="1600" alt="b7414696-dceb-4a76-ac52-ba13117baf5c" src="https://github.com/user-attachments/assets/0529f571-fdca-4178-b08e-29843b06b9da" />

  **MODEL GRAPH:**
  **TABULATION:**
**GRAPH:**
<img width="900" height="1600" alt="d1e194e5-bb32-4d4e-bc59-2b4f48c6458a" src="https://github.com/user-attachments/assets/cbf9e7ac-ac1c-4f0e-a5b8-ac78f14844c5" />

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM AND MODEL GRAPH:**

<<img width="900" height="1600" alt="604552fe-a9e5-417b-b6b7-2c5db9da471c" src="https://github.com/user-attachments/assets/41d67863-aae9-450e-86a7-bef546e7617e" />
  **TABULATION:**
<img width="900" height="1600" alt="de8345ca-a145-46e0-9fee-df8c06b739c0" src="https://github.com/user-attachments/assets/3aa88b23-6c3a-456d-9d9f-68ddeaf44307" />

  **DIFFERENTIAL AMPLIFIER:**

  **CIRCUIT DIAGRAM AND MODEL GRAPH**
<img width="900" height="1600" alt="c815dd74-86f9-4ef3-b0a3-eaea8ebaccb6" src="https://github.com/user-attachments/assets/050ff8b0-df11-4b65-8e31-4c4fec28d3db" />


  **TABULATION:**

<img width="900" height="1600" alt="9e90cead-6ba7-46f0-aae2-710d92b2bb91" src="https://github.com/user-attachments/assets/95a1ae15-9a14-407d-aacb-72e0a70dca1f" />

**GRAPH:**
<img width="900" height="1600" alt="3bdf0979-2191-4883-8410-4d8b4561889e" src="https://github.com/user-attachments/assets/6318fad1-fec9-4b21-90c7-e9c9458d77f3" />

**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  <img width="1600" height="897" alt="2827fbbf-ddac-488f-a967-d37a124fd05e" src="https://github.com/user-attachments/assets/9a28fef0-2679-4427-b3b0-9126d925fc9e" />

<img width="1600" height="829" alt="8c7a0cb3-d0b8-43f9-a136-4a0fee1d5a93" src="https://github.com/user-attachments/assets/628aa1d2-2c3a-424b-b51a-fb5f847ded9e" />

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






