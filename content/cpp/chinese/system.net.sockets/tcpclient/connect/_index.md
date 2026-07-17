---
title: Connect()
second_title: Aspose.Slides for C++ API 参考
description: 建立与指定远程主机的连接。
type: docs
weight: 248
url: /zh/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) 方法

建立与指定远程主机的连接。

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 要连接的远程主机名。 |
| port | **int32_t** | 要连接的远程主机端口。 |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) 方法

建立与指定远程主机的连接。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 远程主机的 IP 地址。 |
| port | **int32_t** | 要连接的远程主机端口。 |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) 方法

建立与指定远程主机的连接。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 要连接的远程主机。 |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) 方法

建立与指定远程主机的连接。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 远程主机的 IP 地址列表。 |
| port | **int32_t** | 要连接的远程主机端口。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [TcpClient](../)
* 类 [IPAddress](../../../system.net/ipaddress/)
* 类 [IPEndPoint](../../../system.net/ipendpoint/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)