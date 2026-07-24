---
title: Connect()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Verbindung zum angegebenen Remote-Endpunkt her.
type: docs
weight: 560
url: /de/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) Methode


Stellt eine Verbindung zum angegebenen Remote-Endpunkt her.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Der Remote-Endpunkt. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) Methode


Stellt eine Verbindung zum angegebenen Remote-Endpunkt her.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Die IP-Adresse des Remote-Hosts. |
| port | **int32_t** | Die Portnummer des Remote-Hosts. |

## Socket::Connect(String, int32_t) Methode


Stellt eine Verbindung zum angegebenen Remote-Endpunkt her.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | [String](../../../system/string/) | Der Remote-Host-Name. |
| port | **int32_t** | Die Portnummer des Remote-Hosts. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) Methode


Stellt eine Verbindung zum angegebenen Remote-Endpunkt her.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Die IP-Adressen des Remote-Hosts. |
| port | **int32_t** | Die Portnummer des Remote-Hosts. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [EndPoint](../../../system.net/endpoint/)
* Klasse [Socket](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Klasse [String](../../../system/string/)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)