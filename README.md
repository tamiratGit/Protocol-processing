# Protocol-processing
Hello group.

I've took libery, and have made GitHub repository for course project.
I am not sure, how this works in Windows, but if you to start, you should create directory for project.
Install github(this i dont know how to in Win)
Navigate to project directory, and do _git clone https://github.com/sginne/Protocol-processing.git_

After this is done, you will get README.md, and possibly some other files from repository, which are of the moment not there yet.

Feel free to play around, if you want to commit changes you've made to local files, you've got to add file
_git add README.md_
_git add dummy.txt_

or just _git add *_

You can check status of repository - _git status_

Ok, now all necessary files added, but changes still reflected only localy.

To make changes appear in repository, you've got to

_git commit -m "First commit"_
_git push_

Here you go, have fun, please add something(like name) to dummy.txt

Here is short sequence to do just that:

_git clone https://github.com/sginne/Protocol-processing.git_ (Clones remote repository locally)
_cd Protocol-processing_ (Traverse into newly created directory)
_kate dummy.txt_ (you might use something else for editting, of course)
_git add dummy.txt_ (Allegedly you want to update dummy.txt)
_git commit -m "Comment"_ (Commits with short message)
_git push_ (Pushes local files to remote repository)

-Timo Junolainen
