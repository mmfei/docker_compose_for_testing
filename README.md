# docker-compose.frp.client.yml
```

```

# docker-compose.nginx.rmtp.yml

## push stream to server
```
ffmpeg -re -i ./static/18_GP095773.MP4 -c copy -f flv rtmp://127.0.0.1:1935/teststream1
```
## play stream in client
```
Using vlc open network url
```