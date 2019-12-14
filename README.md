# could-not-findan-available-non-overlapping-ipv4-address-pool-amoong-the-defaults-to-assign

```
docker network rm $(docker network ls | grep "bridge" | awk '/ / { print $1 }')
```
