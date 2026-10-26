---
title: TcpListener()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar.
type: docs
weight: 53
url: /nl/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) constructor

Construeert een nieuw exemplaar.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Het lokale endpoint waaraan de luistersocket moet worden gebonden. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) constructor

Construeert een nieuw exemplaar.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Het lokale IP-adres. |
| port | **int32_t** | Een poortnummer om te luisteren. |

## TcpListener::TcpListener(int32_t) constructor

Construeert een nieuw exemplaar.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| port | **int32_t** | Een poortnummer om te luisteren. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [TcpListener](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)