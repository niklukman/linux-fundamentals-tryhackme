# Linux Fundamentals TryHackMe

Linux fundamentals is part of complete beginner path.

[Linux Fundamentals Part1](./Part-1)

### Commands

- `echo` - display a line of text
- `whoami`
- `ls`
- `cd`
- `cat`
- `pwd`
- `find`
- `grep`

### Shell operators

- `&` - execute commands in the background.
- `&&` - chaining commands. Execute subsequence command only if the previous command was successful.
- `\>` - output redirector. Will rewrite the content of the file.
- `\>\>` - output redirector. Will append the output to the end of the content without overwriting it.

[Linux Fundamentals Part2](./Part-2)

[Linux Fundamentals Part3](./Part-3)

### Text Editor

- `nano`
- `vim`

### Useful Utilities

#### Downloading Files

- `wget` - download files from the web via http

...
wget https://assets.tryhackme.com/img/logo/tryhackme_logo_full.svg
...

#### Transferring files and directories via ssh

- `scp` - secure copy via ssh

...
scp [source] [destination]

// secure copy from local to remote
scp hello.txt ubuntu@192.168.1.30:/home/ubuntu/world.txt

// secure copy from remote to local
scp ubuntu@192.168.1.30:/home/ubuntu/documents.txt notes.txt
...
