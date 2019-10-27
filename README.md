# Nginx

## How to run
```
docker run -dit --rm --name slowloris-nginx -p 80:80 ppecheny/slowloris-nginx
```


## How to see logs
```
docker logs -f slowloris-nginx
```


# Slowloris attack

## How to run
```
docker run -it --rm ppecheny/slowloris-python python3 slowloris.py 172.17.0.1
```

_172.17.0.1_ - it is docker internal IP, but you can put any host here