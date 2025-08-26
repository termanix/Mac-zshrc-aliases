# Mac-zshrc-aliases


@NeffIsBack's git aliases for Kali have been ported to Mac.

```bash
echo 'alias gapa="git add --patch"
alias gaa="git add --all"
alias gcmsg="git commit -m"
alias gl="git pull"
alias gp="git push"
alias gss="git status -s"
alias gcb="git checkout - "

source ~/.git-prompt.sh
GIT_PS1_SHOWUPSTREAM=""

setopt PROMPT_SUBST 
PROMPT="%F{green}┌─ %n@%m -[%~]%f \$(__git_ps1 ' (%s)') 
%F{green}└─%f$ "' >> ~/.zshrc

curl -L https://raw.github.com/git/git/master/contrib/completion/git-prompt.sh >> ~/.zshrc
```
