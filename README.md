# Full_adder
AIM:
To design a Full Adder circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime

Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.
Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin
Carry = AB + ACin + BCin
 <img width="703" height="365" alt="Screenshot 2025-12-14 220112" src="https://github.com/user-attachments/assets/180dfee2-c87d-4317-acfc-c2b4175ab4aa" />

Truthtable

<img width="332" height="138" alt="Screenshot 2025-12-14 220406" src="https://github.com/user-attachments/assets/f94897e6-4beb-4974-a165-661e0ee9d754" />


Procedure
Write the detailed procedure here

Program:
/* Program to design a  full adder circuit and verify its truth table in quartus using Verilog programming. Developed by:YUVASREE S RegisterNumber: 25014102*/

RTL Schematic

Output Timing Waveform

Result: Thus, the Full Adder circuits are designed and the truth tables is verified using Quartus software.

