setup proxy to api server from master 

```
kubectl proxy --address='0.0.0.0' --port=6753 --accept-hosts='^.*' &
```
