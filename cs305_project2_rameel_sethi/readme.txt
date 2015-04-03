Rameel Sethi
CS 305
Project 2
Implementing a Reliable Transport Protocol

HOW TO RUN:

1.  Unzip the folder:
	$ unzip cs305_project2_rameel_sethi
2.  Enter the newly created directory:
	$ cd cs305_project2_rameel_sethi
3.  Make sure the files rdt.c and input.txt are present.
4.  If you want to change the simulation inputs, enter one quantity on each of these 5 lines of input.txt:
    Line 1: Number of messages to simulate
    Line 2: Packet corruption probability
    Line 3: Packet loss probability
    Line 4: Average time between messages
    Line 5: Trace level (0 to turn off, 1 for basic info, 2 for extended info, 3 or more for debugging info)
5.  Compile the C program: 
	$ gcc -o rdt rdt.c
6.  Delete any previous output.txt files.
7.  Run the program, getting input from input.txt and dumping output to a file (say output.txt):
	$ ./rdt < input.txt > output.txt
8.  Inspect the newly created output.txt for the program output.