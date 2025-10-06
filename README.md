# Bash-Scripting

#To run a bash script you need to make sure to check this list  
  1. always add this line #!/bin/bash in your script in the begining of the script to find the interpretor use [echo $shell] in ternimal if the inter is different then run this [where bash] and get the result and use the result in the place of /bin/bash
  2. when script is ready or in any phase before running make sure to make it executalbe by running [chmod +x (yourscriptname)] if command not work try with sudo.
  3. you can add .sh but if you dont it does not matter because you add this line /bin/bash in your script.
  4. to run the script just type this [./(yourscriptname.sh)] and run your script will run

some other basics-
 -use echo(tells the intreprator to write plain text) like echo $"hello world" output hello world and some other command
 -can also simply type any commnd like ls, pwd, date, etc

#Variables
 -in my script i will add all the scripts in one script as i continue and also add each script seperate.
 -var contains value
 -its recomended to use loweercase in variables, not in value
 -to run a command through a var use this eg:- files= $(ls)
 
