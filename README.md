
# DSCI 521: Lecture 3

 - `add <FILENAME>` : adding <FILENAME> to the staging area
 - `commit -m "MESSAGE"` : commit with a messag everything in the staging area
 - `push <WHERE> <WHAT>` : pushes the history / commits to the remote (where) using the commits from specified branch (what)
 - `pull <WHERE> <WHAT>` : pulls (updates) the local repo with contents in the remote (where) using information in the specifified branch (what)
 - `log` : shows the log
    - `log --oneline`: shows the log in condensed (concise) format
    - this may open a terminal program called `less` that lets you scroll
    - use `q` to escape out of `less`
 - `diff` : shows the "differences" betwwen your changes and the last known git state
   - `diff -staged ` : shows you the diff of the files in the staging area
 - `resote --staged <FILE>` : usstage added file from staging area
 - `revert <SHA1>` : undo the changes in commit in <SHA1>
