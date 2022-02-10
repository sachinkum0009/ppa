# ppa
My PPA Repository


## usage

```bash
curl -s --compressed "https://sachinkum0009.github.io/ppa/KEY.gpg" | sudo apt-key add -

sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://sachinkum0009.github.io/ppa/my_list_file.list"

sudo apt update

sudo apt install hello-deb

sudo apt remove hello-deb
```
