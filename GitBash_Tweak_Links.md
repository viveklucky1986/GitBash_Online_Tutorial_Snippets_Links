#### Git asks for Passphrase for RSA Private Key everytime ####
https://superuser.com/questions/1010542/how-to-make-git-not-prompt-for-passphrase-for-ssh-key-on-windows  
```gitbash
eval `ssh-agent -s`
ssh-add ~/.ssh/*_rsa

eval `ssh-agent -s` && ssh-add ~/.ssh/*_rsa
```
```bash
eval `ssh-agent -s`
ssh-add ~/.ssh/*_rsa

eval `ssh-agent -s` && ssh-add ~/.ssh/*_rsa
```
```sh
eval `ssh-agent -s`
ssh-add ~/.ssh/*_rsa

eval `ssh-agent -s` && ssh-add ~/.ssh/*_rsa
```
