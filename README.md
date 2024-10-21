# EXPERIMENT--01-ALP-FOR-8086
Name :Srinath N
Roll no 2305003009
Date of experiment :27.10.2021





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


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT
## Output  
 ![Screenshot 2024-10-14 143246](https://github.com/user-attachments/assets/9ffa907f-a0ca-4809-81af-e7b0d8f2e65f)

## Subtraction   of 8 bit numbers  ALP 
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT
## Output  
![Screenshot 2024-10-14 143611](https://github.com/user-attachments/assets/d7957db0-bafc-4e1a-88d5-0a7d2f4fe534)

## Multiplication alp 
MOV AL,75H
MOV BL,32H
MUL BL
HLT
 ## Output  
![Screenshot 2024-10-14 143714](https://github.com/user-attachments/assets/57c34200-5203-45a6-ad8d-58d95a87a63b)


## Division alp 
MOV AL,68H
MOV BL,18H
DIV BL
HLT

## Output  
![Screenshot 2024-10-14 143936](https://github.com/user-attachments/assets/33495ebb-a86f-4c8e-b48d-62eeed650e3e)

## AND of 8 bit ALP
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
## OUTPUT
![Screenshot 2024-10-14 154607](https://github.com/user-attachments/assets/deb588d6-84ea-42d3-86cf-60425e0a147c)
## OR of 8 bit ALP
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
## OUTPUT
![Screenshot 2024-10-14 144120](https://github.com/user-attachments/assets/162c7e13-6fde-41fd-9f66-25b93fd79f16)
## NOT of 8 bit ALP
MOV AL,65H
NOT AL
HLT
## OUTPUT
![Screenshot 2024-10-14 144211](https://github.com/user-attachments/assets/2ee2118f-afe8-45d4-a3c4-fb748382846d)
## XOR of 8 bit ALP
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
## OUTPUT
![Screenshot 2024-10-14 144258](https://github.com/user-attachments/assets/1ecc815b-45af-40cd-b7f3-e488786fd555)
## Result :
Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified
successfully.
 








