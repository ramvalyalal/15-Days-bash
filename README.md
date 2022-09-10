# 15-Days-bash

Day1 
Bash Scripting 


echo: It  is a Bash builtin command that writes the arguments it receives to the standard output.


=>Display Hello world 
Using Interactive Shell 
      
echo “Hello world”

Output:
Hello world


Using Non-Interactive Shell 
Commands
-create a file{ touch helloworld.sh}
-write code { vim helloworld.sh}
#!/bin/bash
echo “Hello world”

-execute permission
 chmod +x helloworld.sh

-Run code 
 ./helloworld.sh


Note: If /bin/bash PATH don’t exits then you should use /usr/local/bin/bash


=> Quote in String
There are two types of quoting:
   -double quote 
   -single quote

Display single quote 
       -script
 echo “ Name:’Valya’ “
  Output:
 Name:’Valya’

Display Double quote
      -script

   echo  “Country:\”India”\ “
  
  Output:
   Country:”India”



=> Display all command

  -script
#!/bin/bash  -x 

echo “hello world”


 -output 
  +echo hello world 
hello world



  



