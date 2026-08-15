---
title: Connect()
second_title: Aspose.Slides for C++ API 參考
description: 建立與指定遠端端點的連線。
type: docs
weight: 560
url: /zh-hant/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) 方法

建立與指定遠端端點的連線。

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) 方法

建立與指定遠端端點的連線。

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 遠端主機 IP 位址。 |
| port | **int32_t** | 遠端主機的埠號。 |

## Socket::Connect(String, int32_t) 方法

建立與指定遠端端點的連線。

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 遠端主機名稱。 |
| port | **int32_t** | 遠端主機的埠號。 |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) 方法

建立與指定遠端端點的連線。

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 遠端主機的 IP 位址。 |
| port | **int32_t** | 遠端主機的埠號。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)