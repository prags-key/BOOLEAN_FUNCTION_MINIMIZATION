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
```
 /* Program to implement the given logic function and to verify its operations in quartus
 using Verilog programming.
 module exp2(a,b,c,d,w,x,y,z,f1,f2);
 input a,b,c,d,w,x,y,z;
 output f1,f2;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 assign f2=((~y&z)|(x&y)|(w&y));
 endmodule

Developed by:PRAGATHI KUMAR
 RegisterNumber:24006285
*/
```


**RTL realization**
![Screenshot 2024-12-09 092500](https://github.com/user-attachments/assets/0b2d2c75-609d-4a95-ac4a-a95cda060a60)

**RTL**
![Screenshot 2024-12-09 092500](https://github.com/user-attachments/assets/1f7cd895-d6b7-42d2-82ac-ca4ac0a3c45e)



**Timing Diagram**
![Screenshot 2024-12-09 092520](https://github.com/user-attachments/assets/a15a65a7-31ab-47df-9996-9fa72be56ec7)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

