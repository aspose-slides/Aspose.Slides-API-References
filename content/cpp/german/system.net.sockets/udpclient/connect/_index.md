---
title: Connect()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Verbindung zum angegebenen Port auf dem angegebenen Host her.
type: docs
weight: 66
url: /de/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) Methode

Stellt eine Verbindung zum angegebenen Port auf dem angegebenen Host her.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Der Name des entfernten DNS-Hosts, zu dem Sie eine Verbindung herstellen möchten. |
| port | **int32_t** | Die lokale Portnummer, von der aus Sie kommunizieren möchten. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) Methode

Stellt eine Verbindung mit dem Host an der angegebenen Adresse und dem angegebenen Port her.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Der [IPAddress](../../../system.net/ipaddress/) des entfernten Hosts, an den Daten gesendet werden sollen. |
| port | **int32_t** | Die lokale Portnummer, von der aus Sie kommunizieren möchten. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) Methode

Stellt eine Verbindung zu einem entfernten Endpunkt her.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Der Endpunkt, an den Sie die UDP-Verbindung binden. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [UdpClient](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)