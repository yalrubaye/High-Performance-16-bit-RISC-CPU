# High-Performance-16-bit-RISC-CPU  

This is a custom-built 16-bit RISC CPU created in Logisim. It’s designed to run programs using a clean and efficient instruction set. The CPU includes all the basic building blocks needed for a working processor and was optimized to run about 20% faster than the original version.  
# How it works  
The CPU follows the RISC (Reduced Instruction Set Computer) style, meaning it uses instructions that execute quickly. It includes:

- A Program Counter to keep track of the current instruction.  
- An Instruction RAM that holds the program.  
- A Decoder that breaks instructions into control signals.  
- A Register File to store and load values.  
- An ALU (Arithmetic Logic Unit) to perform math and logic.  
- A Data Memory to load and store data.  
- An Accumulator to hold temporary results.

It also has a stalling system that pauses the CPU when data isn't ready (like during a memory delay), so the program doesn't crash or run incorrectly.  

# Tools Used  
Logisim  
Python – to create an assembler that loads instructions into memory  

# Achievement  
The design improvements led to a 20% increase in processing speed, which made it faster for running test programs.  
  
Refer to the /results folder for images of the final design.  

# Note  
The source code is not publicly included due to privacy and academic integrity reasons. If you're interested in the implementation or want to discuss the design, feel free to reach out.
