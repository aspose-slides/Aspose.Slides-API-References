---
title: TcpListener()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的實例。
type: docs
weight: 53
url: /zh-hant/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) 建構函式

建立新的實例。

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 必須綁定監聽端點的本機端點。 |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) 建構函式

建立新的實例。

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 本機 IP 位址。 |
| port | **int32_t** | 要監聽的埠號。 |

## TcpListener::TcpListener(int32_t) 建構函式

建立新的實例。

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | 要監聽的埠號。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [TcpListener](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)