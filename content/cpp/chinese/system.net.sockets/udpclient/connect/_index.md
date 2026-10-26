---
title: Connect()
second_title: Aspose.Slides for C++ API 参考
description: 在指定的主机上建立到指定端口的连接。
type: docs
weight: 66
url: /zh/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) 方法

在指定的主机上建立到指定端口的连接。

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 要连接的远程 DNS 主机的名称。 |
| port | **int32_t** | 您打算用于通信的本地端口号。 |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) 方法

在指定地址和端口上与主机建立连接。

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 远程主机用于发送数据的 [IPAddress](../../../system.net/ipaddress/)。 |
| port | **int32_t** | 您打算用于通信的本地端口号。 |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) 方法

建立到远程端点的连接。

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 要绑定 UDP 连接的端点。 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [UdpClient](../)
* 类 [IPAddress](../../../system.net/ipaddress/)
* 类 [IPEndPoint](../../../system.net/ipendpoint/)
* 命名空间 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)