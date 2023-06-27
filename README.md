# Macos aliases for development - using Git mainly

These are some aliases mainly for git mainly that I normally use in my day to day work.

Note: there must be a .zshrc file created, this file should sit in /Users/Mac.user/

- `alias l='ls -lah'`
- `alias commands='(cd ~/ && code .zshrc)'`
- `alias ckn='git checkout -b $branch'`
- `alias ck='git checkout $branch'`
- `alias goel='cd ~/Documents/evolvevacationrental-com/'`
- `alias status='git status'`
- `alias stash='git stash -u'`
- `alias pop='git stash pop'`
- `alias pushc='git push -u origin HEAD'`
- `alias pushcf='git push -u origin HEAD -f'`
- `alias sleepoff='sudo pmset -b sleep 0; sudo pmset -b disablesleep 1'`
- `alias sleepon='sudo pmset -b sleep 5; sudo pmset -b disablesleep 0'`
- `alias ammend='git commit --amend'`
- `alias dicall='git restore .'`
- `alias cp='git cherry-pick $commit'`
- `alias ut='npm test -t $commit -- --watchAll --coverage'`
- `alias mer='git merge --no-ff $branch'`
- `alias abo='git merge --abort'`
- `alias con='git merge --continue'`
- `alias com='git commit -m '`
- `alias fullcheck='yarn typecheck && yarn lint && yarn test'`
- `alias delb='git branch -D'`

`[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion`