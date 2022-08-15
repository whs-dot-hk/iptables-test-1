# iptables-test-1
```sh
sudo iptables -A INPUT -i virbr0 -p tcp --sport 22 -j DROP
# or
sudo iptables -A OUTPUT -o virbr0 -p tcp --dport 22 -j DROP
```
