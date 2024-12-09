# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
![WhatsApp Image 2024-10-29 at 10 50 38_b7f3f1b1](https://github.com/user-attachments/assets/f778cad0-6e88-4b27-948c-7b130699a01d)


**truth table**
![WhatsApp Image 2024-12-09 at 10 10 28_21a47b49](https://github.com/user-attachments/assets/237f0dda-800c-4cb9-a531-75931fd2d890)
![WhatsApp Image 2024-12-09 at 10 10 30_6192e65b](https://github.com/user-attachments/assets/a571b0ad-06c9-41ad-b810-68046ae377c2)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:AISHWARIYA S RegisterNumber:24900840
module exp2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
**RTL realization**
![exp2](https://github.com/user-attachments/assets/e337556b-560c-423f-bca1-c1dc66b630ad)




**RTL**

![Screenshot 2024-10-22 114648](https://github.com/user-attachments/assets/7e3ce688-8ab7-4b65-a6f1-85a6f48e47ad)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

