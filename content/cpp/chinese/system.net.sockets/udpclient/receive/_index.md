---
title: Receive()
second_title: Aspose.Slides for C++ API 参考
description: 返回由服务器发送的数据报。
type: docs
weight: 92
url: /zh/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) 方法

返回由服务器发送的数据报。

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | 一个 [IPEndPoint](../../../system.net/ipendpoint/)，表示发送数据的远程主机。 |

### 返回值

一个字节数组，用于存放接收到的数据。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPEndPoint](../../../system.net/ipendpoint/)
* 类 [UdpClient](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)