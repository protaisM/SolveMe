Welcome to my lab! I'll be back in a few minutes.
Until then, don't do anything I wouldn't do.

### Installation

On a linux console, do
```bash
mkdir SolveMe && cd SolveMe
git clone --mirror https://github.com/protaisM/SolveMe .git
git config --local --bool core.bare false
sed -i "/mirror/d" .git/config
git reset --hard
```

### For Naren and Srikanth

Your goal is to look for a token file. It is not hidden, however you will need to solve
various enigmas to get it.
If you obtain it you know that you finished all the puzzles.
For that, everything is allowed, even though you should not need to enter the .git folder
Enjoy!
