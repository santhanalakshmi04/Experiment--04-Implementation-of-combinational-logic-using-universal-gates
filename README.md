# Experiment--04-Implementation-of-combinational-logic-using-universal-gates
Implementation of combinational logic using universal-gates
 
## AIM:
To implement the given logic function using NAND and NOR gates and to verify its operation in Quartus using Verilog programming.

F=((C'.B.A)'(D'.C.A)'(C.B'.A)')' using NAND gate
F=(((C.B'.A)+(D.C'.A)+(C.B'.A))')' using NOR gate
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
Logic gates are electronic circuits which perform logical functions on one or more inputs to produce one output. 

## Using NAND gates
NAND gate is actually a combination of two logic gates i.e. AND gate followed by NOT gate. So its output is complement of the output of an AND gate.This gate can have minimum two inputs, output is always one. By using only NAND gates, we can realize all logic functions: AND, OR, NOT, X-OR, X-NOR, NOR. So this gate is also called as universal gate. First note that the entire expression is inverted and we have three terms ANDed. This means that we must use a 3-input NAND gate. Each of the three terms is, itself, a NAND expression. Finally, negated single terms can be generates with a 2-input NAND gate acting as an inverted.

F=((C'.B.A)'(D'.C.A)'(C.B'.A)')'

## Logic Diagram

Using NOR gates
NOR gate is actually a combination of two logic gates: OR gate followed by NOT gate. So its output is complement of the output of an OR gate. This gate can have minimum two inputs, output is always one. By using only NOR gates, we can realize all logic functions: AND, OR, NOT, Ex-OR, Ex-NOR, NAND. So this gate is also called universal gate. Designing a circuit with NOR gates only uses the same basic techniques as designing a circuit with NAND gates; that is, the application of deMorgan’s theorem. The only difference between NOR gate design and NAND gate design is that the former must eliminate product terms and the later must eliminate sum terms.

F=(((C.B'.A)+(D.C'.A)+(C.B'.A))')'

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function using NAND and NOR gates and to verify its operations in quartus using Verilog programming.
Developed by: 

RegisterNumber:  
*/
## RTL realization

## Output:

RTL FOR NAND
![214344822-b443edee-f040-41e8-90ab-10ae49bf8791](https://user-images.githubusercontent.com/119475762/214614229-6b28cf4f-8a45-40db-b3a5-86b47659f6f3.png)

FOR NOR
![214345105-928992f9-cca2-4f47-b58c-8b44a6ea292f](https://user-images.githubusercontent.com/119475762/214614435-54eecb9b-a758-430e-a37f-97aeba2482cd.png)

## Timing Diagram FOR NAND
![214345368-9f9d1b67-1387-4696-9882-22de0925401b](https://user-images.githubusercontent.com/119475762/214614650-d478968f-dcaa-4a28-a775-8be5f071c130.png)

FOR NOR
![214345574-c81b6138-4244-40af-8bf3-aa13399349a5](https://user-images.githubusercontent.com/119475762/214614764-21977842-99d8-4707-a52e-cfbfc76311f4.png)

TRUTHTABLE FOR NAND
![214346012-7c77b780-b81e-462f-a5b1-769339ea79fc](https://user-images.githubusercontent.com/119475762/214614963-60604996-7d95-4f8d-b178-cdca58aeaac1.png)

FOR NOR
![214346425-988f69ea-2c0e-4970-9c3c-c2a9b2dee8e8](https://user-images.githubusercontent.com/119475762/214615018-1993ee44-eb45-4f1f-aa20-9fb3f56f476d.png)

## Result:
Thus the given logic functions are implemented using NAND and NOR gates and their operations are verified using Verilog programming.
