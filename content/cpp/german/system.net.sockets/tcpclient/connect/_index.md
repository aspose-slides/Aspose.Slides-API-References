---
title: Connect()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Verbindung zum angegebenen Remote-Host her.
type: docs
weight: 248
url: /de/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) Methode

Stellt eine Verbindung zum angegebenen Remote-Host her.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Ein Remote-Host-Name, zu dem verbunden werden soll. |
| port | **int32_t** | Ein Port des Remote-Hosts, zu dem verbunden werden soll. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) Methode

Stellt eine Verbindung zum angegebenen Remote-Host her.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Die IP-Adresse eines Remote-Hosts. |
| port | **int32_t** | Ein Port des Remote-Hosts, zu dem verbunden werden soll. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) Methode

Stellt eine Verbindung zum angegebenen Remote-Host her.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Ein Remote-Host, zu dem verbunden werden soll. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) Methode

Stellt eine Verbindung zum angegebenen Remote-Host her.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Die IP-Adressen eines Remote-Hosts. |
| port | **int32_t** | Ein Port des Remote-Hosts, zu dem verbunden werden soll. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [TcpClient](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)