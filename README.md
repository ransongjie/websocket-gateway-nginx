# websocket-gateway-nginx
- nginx
- gateway
- websocket
- webhttp

# 过程
建立连接
```
websocket
    index.html
    ws://localhost:9091/one/ws/stomp
    nginx.conf
    http://localhost:9092/two/ws/stomp
    gateway
    ws://localhost:9093/stomp
    websocket
webhttp
    Browser GET
    http://localhost:9091/one/xcrj/name
    nginx.conf
    http://localhost:9092/two/xcrj/name
    gateway
    http://localhost:9094/xcrj/name
    webhttp
```