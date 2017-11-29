#How-To-Add-SSH-Key-to-GitHub

Step 1: Install git first
	
		Open git bash

Step 2: Generate an SSH Key
	
		ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

Step 3: Press Enter

Step 4: Enter passphrase should be the password of computer

Step 5: Enter this to git bash
	
		eval "$(ssh-agent -s)"

Step 6: Enter this
	
		ssh-add ~/.ssh/id_rsa

Step 8: Goto to your github account
		
Step 9: Click Setting

Step 10: Click SSH and GPG Keys

Step 11: Click New SSH Key

Step 12: Fill up title anything you want

Step 13: Goto git bash 

Step 14: type this to command this will copy the id/_rsa
		
		clip < ~/.ssh/id_rsa.pub 
	
Step 15: Goto github account

Step 16: Right click the textbox in key then paste

Step 17: Press Add SSH key

Step 18: Finish
