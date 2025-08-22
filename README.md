# EXPERIMENT--01-ALP-FOR-8086
Name : VEDAGIRI INDU SREE
Roll no : 212223230236
Date of experiment : 22/08/2025
## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen.
7.	
8.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
9.	 
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

10.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
START:
MOV AL,04
MOV BL,03
ADD AL,BL
HLT
```
## Output  
 <img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/58bdd510-5f5b-4180-bd0b-b4dc2a001ad4" />

## Subtraction   of 8 bit numbers  ALP 
 ```
START:
MOV AL,04
MOV BL,03
SUB AL,BL
HLT
```
## Output
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/2b7c52a5-e7fb-406f-840a-ee928405be1b" />

## Multiplication alp 
```
START:
MOV AL,03
MOV BL,03
MUL BL
HLT
```
## Output
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/32ff2588-7b38-4ddd-9364-27b8a569b451" />

## Division alp 
```
START:
MOV AL,06
MOV BL,03
DIV BL
HLT
```
## Output  
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/2639c3a2-17e8-43cd-bd4f-928d868ac165" />

## AND Operation
```
START:
MOV AL,50H
MOV BL,25H
AND AL,BL
HLT
```
## Output
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/f321c322-e057-43b3-b4a3-99afc190c190" />

## OR Operation
```
START:
MOV AL,50H
MOV BL,25H
OR AL,BL
HLT
```
## Output
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/291d98e9-b477-40a3-a150-3ae09a77d916" />

## XOR Operation
```
START:
MOV AL,18H
MOV BL,46H
XOR AL,BL
HLT
```
## Output
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/364102b2-8e90-4475-b47e-04305ab19afd" />

## NOT Operation
```
START:
MOV AL,18H
NOT AL
HLT
```
## Output
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/82e2ffd1-4eff-4f9e-8f45-f16e1c51ba74" />

## Result :
Thus, Alp for fundamental arithmetic and logical operations are exected succesfully.
