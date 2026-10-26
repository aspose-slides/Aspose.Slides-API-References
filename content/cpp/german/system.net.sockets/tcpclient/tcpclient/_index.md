---
title: TcpClient()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 235
url: /de/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Der Endpunkt, an den der Socket gebunden ist. |

## TcpClient::TcpClient() Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Eine Adressfamilie. |

## TcpClient::TcpClient(String, int32_t) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Ein Remote-Hostname zum Verbinden. |
| port | **int32_t** | Ein Port des Remote-Hosts zum Verbinden. |

## Siehe auch

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [TcpClient](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)