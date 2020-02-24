#2020-02-24 Git Basics

- `init` : make the current folder a git respository
- `status` : see the status of the current repository
- `add` : put the files into the index (staging area)
- `commit` commit the files from the staging area
	-`commit -m "MESSAGE" ` : directly put in a single line comment
-`diff` : look at the difference between two states
-`log` : look at the history
	`log --online` : look at the history abbreviated in the one line view
-`checkout <hash><file>` : restore a single file from a point in history
	-`checkout <hash>` : restore the entire folder to that point in time

- index/staging area : files in here will be commited
-`HEAD` : where you are looking in git history

- remote :anywhere you didn't init or clone
- `push` : send the code to our remote
- `pull` : get code from our remote (does a `fetch` and a `merge`)

