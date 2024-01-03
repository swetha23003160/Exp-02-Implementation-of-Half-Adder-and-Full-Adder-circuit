# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure


Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: swetha.m
RegisterNumber: 23003160 
*/






### RTL
halfadder:
![Screenshot 2024-01-03 074602](https://github.com/swetha23003160/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150416143/80069f1a-2166-4096-9500-0b793cd47123)

fulladder:
![Screenshot 2024-01-03 074615](https://github.com/swetha23003160/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150416143/443dc5b1-2b47-4ab0-97e4-80a63115f91f)


### TRUTH TABLE :

halfadder
![Screenshot 2024-01-03 074640](https://github.com/swetha23003160/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150416143/0d3d7c0c-22ca-4fcf-8a6a-9445225c61d3)

fulladder:
![Screenshot 2024-01-03 074645](https://github.com/swetha23003160/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150416143/ebd14042-acec-42eb-9325-f4b90024b98e)

### TIMING DIAGRAM
halfadder
![Screenshot 2024-01-03 074623](https://github.com/swetha23003160/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150416143/09b26cb2-60f4-42f4-abe3-975de24795a3)

fulladder
![Screenshot 2024-01-03 074630](https://github.com/swetha23003160/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150416143/f5e25589-00a6-4d13-b91f-085e7fe3c28d)



### Result:
