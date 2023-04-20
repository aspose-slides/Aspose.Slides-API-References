---
title: TcpListener()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 53
url: /cpp/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | The local endpoint to which the listener socket must be bound. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | The local IP address. |
| port | **int32_t** | A port number to listen. |

## TcpListener::TcpListener(int32_t) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | A port number to listen. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [TcpListener](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)