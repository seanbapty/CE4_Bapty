CE4_Bapty
=========
# Overview
The purpose of this computer exercise was to utulize assembly language programing to solve 3 problems involving memory manipulation, mathematics, and looping. The programming format was designed to work on the PRISM operating system. Below are descriptions of the problems and the opcodes/operands used to solve them.

# Part A
In part A the goal was to write a program that stores the value $9 in location $B0, $8 in $C4 and $B in $CB. This was implemented using the mnemonics LDAI (loads the operand into the accumulator), STA (stores the value in the accumulator in a position given by the operand), and JMP (used to loop through the program to prevent it from crashing.

![alt tag](https://raw.githubusercontent.com/seanbapty/CE4_Bapty/master/partA.JPG)

# Part B
In part B the goal was to write a program that retrieves a value from location $B0, doubles it, and subtracts 4. The below image illustrates the mnemonics used (labeled Instruction) as well as the corresponding opcodes and operands.

![alt tag](https://raw.githubusercontent.com/seanbapty/CE4_Bapty/master/partB.JPG)

# Part C
In part C the goal was to write a program that starts by reading what is on Input Port 3 and then displaying that on Output Port 0.  One less than that was then displayed on Port 1 and one less than what is on Port 1 was displed on Port 2. The program then decrements what is on Port 0, then decrements what is on Port 1, then decrements what is on Port 2.  This process is continued in an infinite loop. The assembly instructions given to PRISM are shown below.

