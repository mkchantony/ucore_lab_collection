ucore_lab_collection
====================

Switch to original labX code (X = 1..8) :
	git checkout vX

Create your branch at this version
	git checkout -b branch myX

Merge from your old branch Y (Y = X - 1)
	git merge tagY

Commit your base code on this lab
	git commit -a -m labX_start

Do your homework now ...

if need to rollback, do
	git checkout *

if finished, do not forget to commit
	git commit -a -m labX_finish

And make a tag for future merge
	git tag tagX
