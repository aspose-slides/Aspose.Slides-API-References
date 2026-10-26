---
title: TcpListener()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 53
url: /de/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Der lokale Endpunkt, an den das Listener-Socket gebunden werden muss. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Die lokale IP-Adresse. |
| port | **int32_t** | Eine Portnummer, auf die gehört wird. |

## TcpListener::TcpListener(int32_t) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| port | **int32_t** | Eine Portnummer, auf die gehört wird. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [TcpListener](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)