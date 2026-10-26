---
title: UdpClient()
second_title: Aspose.Slides for C++ API 参考
description: 初始化 UdpClient 类的新实例。
type: docs
weight: 27
url: /zh/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() 构造函数

初始化 [UdpClient](../) 类的新实例。

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) 构造函数

初始化 [UdpClient](../) 类的新实例。

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | 指定套接字的寻址方案的值。 |

## UdpClient::UdpClient(int32_t) 构造函数

初始化 [UdpClient](../) 类的新实例。

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| port | **int32_t** | 您打算用于通信的本地端口号。 |

## UdpClient::UdpClient(int32_t, AddressFamily) 构造函数

初始化 [UdpClient](../) 类的新实例。

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| port | **int32_t** | 您打算用于通信的本地端口号。 |
| family | [AddressFamily](../../addressfamily/) | 指定套接字的寻址方案的值。 |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) 构造函数

初始化 [UdpClient](../) 类的新实例。 param local EP 本地端点，您将其绑定到 UDP 连接。

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) 构造函数

创建 [UdpClient](../) 类的新实例并在指定端口上连接到指定的远程主机。

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 您打算连接的远程 DNS 主机的名称。 |
| port | **int32_t** | 您打算用于通信的本地端口号。 |

## 参见

* 枚举 [AddressFamily](../../addressfamily/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [UdpClient](../)
* 类 [IPEndPoint](../../../system.net/ipendpoint/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)