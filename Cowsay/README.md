# Aufgabe
Sie sollen mithilfe von go eine alternative von „cowsay“ implementieren. Dabei soll das Programm die 
Zeichenkette als Argument übernehmen und entsprechend formatiert als ASCII-Art ausgeben:

# diese Aufgabe habe ich in main1.go mit scanfunction  
in terminal Befehl sind
            :go mod init example/cow
            :go mod tidy
            :go run main1.go
# und in main2.go mit Argument 
            :go run main2.go "Hello World"

# ****************************************************
# Project name: "Cowsay"implementation
# Project description:
to implement an alternative of "cowsay" with the help of go.
The program is to take the string as an argument and output it formatted accordingly as ASCII type.
***
# Table of Contents
# General info:
to create the code for a cowsay alternative written in golang 
# Screenshot:
image.png
# Installation:
Visual Studio Code
# Packages required:
"bufio" Package bufio implements buffered I/O. It wraps an io.Reader "os" Package os provides a platform-independent interface to operating system functionality.
# Technologies:
scanner function-used to read data from the standard input, format the string, and store the resultant strings into the destinations
for loop- used to repeat a block of code.loop will stop iterating once the boolean condition evaluates to false
# Collabration:
In main.go written code is divived into 3 parts :
line 11-14: scannerfunction,line 18-19,24-25:forloop for the Speech bubble,line 21-22:text inside the Speech bubble.
***
# github:
https://github.com/unicodebinod