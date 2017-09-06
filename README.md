# squid_docker
usage
```
docker-compose up -d --build

iptables -A PREROUTING -i <IFNAME> -p tcp -m tcp --dport 80 -j DNAT --to-destination <EXTIP>:3128

```
