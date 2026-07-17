---
title: Connect()
second_title: Aspose.Slides for C++ API 参考
description: 建立到指定远程端点的连接。
type: docs
weight: 560
url: /zh/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) 方法

建立到指定远程端点的连接。

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程端点。 |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) 方法

建立到指定远程端点的连接。

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 远程主机 IP 地址。 |
| port | **int32_t** | 远程主机的端口号。 |

## Socket::Connect(String, int32_t) 方法

建立到指定远程端点的连接。

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 远程主机名。 |
| port | **int32_t** | 远程主机的端口号。 |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) 方法

建立到指定远程端点的连接。

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 远程主机的 IP 地址。 |
| port | **int32_t** | 远程主机的端口号。 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [EndPoint](../../../system.net/endpoint/)
* 类 [Socket](../)
* 类 [IPAddress](../../../system.net/ipaddress/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)