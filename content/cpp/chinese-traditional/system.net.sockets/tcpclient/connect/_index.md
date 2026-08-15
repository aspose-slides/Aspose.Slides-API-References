---
title: Connect()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立與指定遠端主機的連線。
type: docs
weight: 248
url: /zh-hant/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) method

建立與指定遠端主機的連線。

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 要連線的遠端主機名稱。 |
| port | **int32_t** | 要連線的遠端主機埠號。 |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method

建立與指定遠端主機的連線。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 遠端主機的 IP 位址。 |
| port | **int32_t** | 要連線的遠端主機埠號。 |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) method

建立與指定遠端主機的連線。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 要連線的遠端主機。 |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) method

建立與指定遠端主機的連線。

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 遠端主機的 IP 位址。 |
| port | **int32_t** | 要連線的遠端主機埠號。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)