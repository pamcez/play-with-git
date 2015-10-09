##Play with git

Hello girls, we are going to have fun playing with git. Try to do all the steps listed here to be a git junior.

You don't need anything for this, I mean, you don't need to run it in a server or anything,
we are just working with `.txt` (you can open those files with pretty much anything).

I'm not gonna detailed the actual commands, that's for you to figure out ;)
Shout on the slack channel / meetup discussion board if you are stuck.

####Steps for fun with git

- Clone this repo
    - Extra fake points if you *do* clone the repo in the server, so that you can see it in the broswer if you go to an address like `http://localhost/stripegirls-list.txt`. This is in prep for creating the site repo for next meetup.
- If you are not on it already, checkout the `master` branch
- Have a look at the folder where the repo was cloned, you should have at least this
`README.md` file and a `stripegirls-list.txt` file (and other lot of files if another stripegirl has completed this already)
- Open up `stripegirls-list.txt` and add your name to the end of the list
- Save the file, and commit it in the `master` branch.
    - If you want to go deep down the rabbit hole, read [how to write a great commit message](http://chris.beams.io/posts/git-commit/). Every developer in the world will love you.
- Push your changes to `origin/master` (that means is visible when you go to the github account and look at the repo history)
- Create a branch from master, called `feature-xxx` where `xxx` is your name/nickname
- Checkout that new created branch and add a file called `intro-xxx.txt` where `xxx` is your name again.
- Edit that file and add a message or something. Save it.
- Push your new branch and file to github (also called `origin` or "remote").
- At this step you can freely jump from your branch to `master` and back, and see the differences. `master` shouldn't have your newly created file, but if you jump back to the branch, the file is going to be there.

If you got here, then you already know a lot of what we'll use for the repo. The last step will be to merge `feature-xxx` to `master`.

If you want to be pro-er (or "more pro"), let's keep doing stuff...
- Now, checkout `master`, open `stripegirls-list` and next to your name add an [emotik](http://japaneseemoticons.me/) that represents you (like **(ﾉ^ヮ^)ﾉ*:・ﾟ✧** )
- Commit to master and push to origin.
- Checkout `feature-xxx`. Notice we don't have the emotik change we did on master.
- Rebase `master` into `feature-xxx`. Now we should have the latest change from master in the feature branch.
- Aaand now merge `feature-xxx` into `master`.
- Admire your amazingness.