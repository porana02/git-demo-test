git-demo-test
=============

The quick brown fox jumps over the lazy dog.

Time flies like an arrow. Fruit flies like a banana.

###Before Training
1. Download and install github for windows version 2 from https://windows.github.com/
2. log in with your github credentials and follow any instructions

###git/github training repository for
- Nate
- Cindy
- Jean (this is my change)

###markdown help
1. https://help.github.com/articles/markdown-basics
1. https://help.github.com/articles/github-flavored-markdown


###During Training
1. fork git-demo-test on github.com
2. clone git-demo-test in github for windows 2 (your fork, not Luther College's)
3. edit your sql file in a text editor and save it
4. commit your changes in github for windows 2
5. sync your changes in github for windows 2
6. on the github website go to your fork of git-demo-test
7. find the green pull request button and press it
8. comment on your changes
9. submit it


Hello!!!


10. back on your own computer repeat 3-9 but edit the README.md file instead
11. you may notice you don't have changes made by others on your fork (on github or locally)
12. Click the gear in the top right corner of github for windows and choose to open the shell.
13. type `git remote add upstream https://github.com/luther_college/git-demo-test.git` (this may have been done automatically by github for windows, but this is what you would do to add a remote)
14. type `git fetch upstream`
15. type `git merge upstream/master`
16. You now have your local files up to date with the remote (although you may have some merge conflicts to deal with in README.md)
17. Once you have looked at and dealt with any merge conflicts commit and sync. Clicking sync will actually do many commands behind the scenes. First, it will fetch from your origin (your forked version of the repository.) Then it will merge any changes into your local (on your computer), then it will push your local commits up to your github repository (the one with your username before the "git-demo-test.") If you log on to github you will now see your repository matches Luther College's repository. You would likely do this process before you would work on a piece of code.
18. If, even after syncing, github for windows doesn't push your changes to your fork on github you can try manually pushing them by typing `git push origin` For some reason my sync button wasn't pushing when I was testing this workflow.




