# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.



## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: SOWMYA BADONI
RegisterNumber:  23001999


## CODE:
## HALF SUBTRACTOR:
![Exp4 hs code](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/8879bf54-5e2f-470b-97e0-8ef5a4cafa48)

## FULL SUBTRACTOR:
![Exp4 fs code](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/91586a8d-4d17-4be0-8e4c-2d25e6fadbfc)

## OUTPUT

## Truthtable
## HALF SUBTRACTOR:
![Exp4 truthtable hs](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/23c3a9ce-5eac-43e0-9b4a-c1b41af72209)

## FULL  SUBTRACTOR:
![Exp4 truthtable fs](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/d9707fe5-a710-4af8-9a80-2384bd6916e8)



##  RTL:
## HALF SUBTRACTOR:
![Exp4 hs RTL diagram](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/648c7631-7216-4a76-8b0b-f739e3faeea5)


## FULL SUBTRACTOR:
![Exp4 fs RTL diagram](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/566c3751-e2c2-46fa-896a-6e15d2ce404b)




## Timing diagram:
## HALF SUBTRACTOR:
![hs wave](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/63e3f85d-4270-4c02-aa04-ac34515d26a3)

## FULL SUBTRACTOR:
![fs wave](https://github.com/sowmya-badoni/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152136324/2fd3547f-ec97-40ee-a7db-1d8e28ca49ef)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
