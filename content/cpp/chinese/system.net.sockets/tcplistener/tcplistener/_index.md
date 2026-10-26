---
title: TcpListener()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 53
url: /zh/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) 构造函数

构造一个新实例。

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 必须绑定监听套接字的本地终结点。 |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) 构造函数

构造一个新实例。

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 本地 IP 地址。 |
| port | **int32_t** | 要监听的端口号。 |

## TcpListener::TcpListener(int32_t) 构造函数

构造一个新实例。

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| port | **int32_t** | 要监听的端口号。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPEndPoint](../../../system.net/ipendpoint/)
* 类 [TcpListener](../)
* 类 [IPAddress](../../../system.net/ipaddress/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)