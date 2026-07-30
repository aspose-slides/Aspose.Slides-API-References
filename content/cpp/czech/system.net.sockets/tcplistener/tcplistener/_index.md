---
title: TcpListener()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří novou instanci.
type: docs
weight: 53
url: /cs/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Lokální koncový bod, ke kterému musí být svázán socket posluchače. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Lokální IP adresa. |
| port | **int32_t** | Číslo portu, na kterém naslouchat. |

## TcpListener::TcpListener(int32_t) konstruktor


Vytvoří novou instanci.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| port | **int32_t** | Číslo portu, na kterém naslouchat. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPEndPoint](../../../system.net/ipendpoint/)
* Třída [TcpListener](../)
* Třída [IPAddress](../../../system.net/ipaddress/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)