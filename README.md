imple shell
The project, simple shell is the final project of the first trimester in ALX-SE Program, is about building a program as similar as possible to the unix shell using the programming language C.

This project was built by Aron Asgedom and Selam Aynehuba.

Table of Contents
Authors
How Use
.explanation
Authors
👤 Aron Asgedom Abay

Github: @aronisha
E-mail: @aronasgedom@gmail.com 
👤 selam Aynehubah


How Use
How to compile
Requirements
All your files will be compiled on Ubuntu 20.04.2 LTS
Your C programs and functions will be compiled with gcc 9.3.0
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
No more than 5 functions per file
Flags to compile
$ gcc -Wall -Werror -Wextra -pedantic *.c

Explanation
Non interactive
pass the commands in the stdin but no prints the prompt.

$ echo "ls" | ./hsh

interactive
the program is execute and the prompt is print, and wait for the user.

$ ./hsh ($)
