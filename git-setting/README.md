# Git Setting

## Download Git

```
$ sudo apt update
$ sudo apt install
```

## Set SSH

```
$ ssh-keygen -t rsa -C "your_email@example.com"
$ eval "$(ssh-agent -s)"
$ ssh-add ~/.ssh/id_rsa
$ cat ~/.ssh/id_rsa.pub
```
Copy the context of ~/.ssh/id_rsa.pub
Paste to <https://github.com/settings/ssh/new>

## References

About SSH key

<https://nickjoit.tistory.com/94>
