1.`git init ` -> powers your folder managed by git, initialize a new empty Repository.
it also Creates a .git folder that has all relevant logic to manage version of you project.

2.`working area` -> there can be a bunch of filesthat are not currently handled by git.
that means change done or to be done in those files are manage by git yet .a file which is in working area 
is considered to be not in the stageing area when we do `git status` and we see a bunch if `untracked files`.
the these are actually call a woring area .

3. `Staging Area ` -> what all files are goint to be part of the next vesioonthat we will create .
this staging area is the place where git knows what change will be done from th last version to the next version 

4.`Repository Area` -> this area actually contain the details of all you previous registered version and the files in this area git already
manages them and kniws there version history.


5. `git add <file> ` -> moves files from working area to staging area 

6. `git rm --cached <file> `-> moves files back from staging area to working area .

7.`commit` -> commit is a particukar version of the project .it capture the snapshots of the projects 
staged changes and creaes a version outof it .

8 . `git commit `  -> registers staging changes to a commit.

9 . `git log` -> list down all the commits of the repository.
 if you want to exit from git log just press q.

10. `git restore <file>` --> it remove all file changes from the staging area.this can be useful .
if we did some dirt piece of code and now we no more want it instead of deleting it one by one , we can restore 
it or you can say restore last version of of the file .

