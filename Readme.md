This is to set up git


git process flow

# Location of the public ssh key: c/users/user/.ssh/id_ed25519.pub

1- create a repository in Github portal, repository name: Gitproject01

2- Set up the Gitbash Workspace
		2-1 mkdir Gitproject01		# to create the workspace
		2-2 cat >> (or >) abc.txt   # to create a file (s)

4- git init 						#initiliase git

5- git status 						# to check the status of files and folders created or ammended. 

6- git config --global				#Globlal parameter config. Choices of parameters are: Globlal, System and Local
		6-1  user.name
		6-2 git config --global user.email
		6-3 git config --list verify config parameter

7- git add 							# Track changes (stage files ready to commit
		7-1 add . 					# for all files within the directory
		7-2 add abc.txt 			# for specific files within the folder

8- git commit -m 					#commit file to local repository

9- git log 							# view logs and changes being tracked

10- git remote  add origin git@github:rcn1ect/Gitproject01	#connect to the node/local database to github portal. use SSH config as https protoco is deprecated

11- git push origin main			#push the code to from the laptop to github portal

12 Cross verify
		12-1 The files/folders have been synced between the portal and gitbash
		12-2 Commit numbers between git bash and the repository on github portal are the same

13- git clone

14- git log

15- Git show
		15-1 show 					# show all commits performed; expect to see semi-column (:) at the end of the page if  the list is longer than a page
		15-2 show "commit number" 	# to see the content of a specific change


