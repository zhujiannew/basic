This is a testing project used for exploring C++ large project structure.

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/zhujiannew/basic.git
git push -u origin master

git remote add origin https://github.com/zhujiannew/basic.git
git push -u origin master

startup ssh agent under windows
================================
PS C:\WINDOWS\system32> Set-Service -Name ssh-agent -StartupType Manual
PS C:\WINDOWS\system32> Start-Service ssh-agent

add the private key
ssh-add id_rsa