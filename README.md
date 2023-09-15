# how to use tor and torsocks in Ubuntu
1. Install tor
```bash
sudo apt update
sudo apt install tor
tor --version
source torsocks on

```

check:
```bash
wget -qO - https://api.ipify.org; echo
```
FIrefox network settings: 

localhost port 9050 
SOCKS v5

Then restart tor
```bash
sudo systemctl restart tor
```
