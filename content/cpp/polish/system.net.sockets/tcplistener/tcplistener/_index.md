---
title: TcpListener()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową instancję.
type: docs
weight: 53
url: /pl/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Lokalny punkt końcowy, do którego musi być podłączone gniazdo nasłuchujące. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Lokalny adres IP. |
| port | **int32_t** | Numer portu do nasłuchiwania. |

## TcpListener::TcpListener(int32_t) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| port | **int32_t** | Numer portu do nasłuchiwania. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPEndPoint](../../../system.net/ipendpoint/)
* Klasa [TcpListener](../)
* Klasa [IPAddress](../../../system.net/ipaddress/)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)