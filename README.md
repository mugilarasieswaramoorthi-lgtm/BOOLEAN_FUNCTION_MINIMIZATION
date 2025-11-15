# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule


Developed by:MUGILARASI E

RegisterNumber: 25017644


**RTL realization**

**Output:**
<img width="1919" height="1079" alt="Screenshot 2025-11-15 220431" src="https://github.com/user-attachments/assets/2bc75435-5c2a-435d-84e8-f19ac4e3329e" />


**RTL**

**Timing Diagram**
<img width="1919" height="1078" alt="Screenshot 2025-11-15 220414" src="https://github.com/user-attachments/assets/e8740976-61c7-4f3b-b78c-5b6c691511c2" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

