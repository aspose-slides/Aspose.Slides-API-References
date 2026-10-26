---
title: Send()
second_title: Aspose.Slides for C++ API 参考
description: 将 UDP 数据报发送到远程端点的主机。
type: docs
weight: 79
url: /zh/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) 方法

将 UDP 数据报发送到位于远程端点的主机。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的 [Byte](../../../system/byte/) 类型数组 |
| bytes | **int32_t** | 数据报中的字节数。 |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 表示要发送数据报的主机和端口的 [IPEndPoint](../../../system.net/ipendpoint/)。 |

### 返回值

已发送的字节数。

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) 方法

将 UDP 数据报发送到指定远程主机上的指定端口。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的 [Byte](../../../system/byte/) 类型数组 |
| bytes | **int32_t** | 数据报中的字节数。 |
| hostname | [String](../../../system/string/) | 远程主机的名称。 |
| port | **int32_t** | 远程端口号。 |

### 返回值

已发送的字节数。

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) 方法

将 UDP 数据报发送到远程主机。

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的 [Byte](../../../system/byte/) 类型数组。 |
| bytes | **int32_t** | 数据报中的字节数。 |

### 返回值

已发送的字节数。

## 另请参阅

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPEndPoint](../../../system.net/ipendpoint/)
* 类 [UdpClient](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)