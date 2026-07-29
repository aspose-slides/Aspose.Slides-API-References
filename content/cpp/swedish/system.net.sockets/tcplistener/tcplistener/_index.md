---
title: TcpListener()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 53
url: /sv/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) konstruktor


Skapar en ny instans.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Den lokala slutpunkten som lyssnarsockeln måste bindas till. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) konstruktor


Skapar en ny instans.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Den lokala IP-adressen. |
| port | **int32_t** | Ett portnummer att lyssna på. |

## TcpListener::TcpListener(int32_t) konstruktor


Skapar en ny instans.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| port | **int32_t** | Ett portnummer att lyssna på. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPEndPoint](../../../system.net/ipendpoint/)
* Klass [TcpListener](../)
* Klass [IPAddress](../../../system.net/ipaddress/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)