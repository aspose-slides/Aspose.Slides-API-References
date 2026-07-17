---
title: TcpClient()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 235
url: /zh/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) 构造函数


构造一个新实例。

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 绑定套接字的端点。 |

## TcpClient::TcpClient() 构造函数


构造一个新实例。

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) 构造函数


构造一个新实例。

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | 地址族。 |

## TcpClient::TcpClient(String, int32_t) 构造函数


构造一个新实例。

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 要连接的远程主机名。 |
| port | **int32_t** | 要连接的远程主机端口。 |

## 另请参见

* 枚举 [AddressFamily](../../addressfamily/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPEndPoint](../../../system.net/ipendpoint/)
* 类 [TcpClient](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)