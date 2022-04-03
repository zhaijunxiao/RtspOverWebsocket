# RtspOverWebsocket
一个解析Rtsp Over Websocket 的Wireshark C插件

Websocket默认只是Websocket包的解析，但是美中不足的是，它在解析完Websocket的包头后，不会继续解析之后的数据。
本插件的作用是：在解析完Websocket包头之后，显式的以Rtsp方式继续解析剩下的数据。

# 如何使用
参见博客：https://www.yinxiang.com/everhub/note/cede3cb5-9410-45c6-98c2-cfe5343ba590
