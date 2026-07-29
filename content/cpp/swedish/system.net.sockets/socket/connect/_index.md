---
title: Connect()
second_title: Aspose.Slides för C++ API-referens
description: Etablerar en anslutning till den angivna fjärrslutpunkten.
type: docs
weight: 560
url: /sv/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) metod


Etablerar en anslutning till den angivna fjärrslutpunkten.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Fjärrslutpunkten. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) metod


Etablerar en anslutning till den angivna fjärrslutpunkten.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Fjärrvärdens IP-adress. |
| port | **int32_t** | Portnumret för fjärrvärden. |

## Socket::Connect(String, int32_t) metod


Etablerar en anslutning till den angivna fjärrslutpunkten.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | [String](../../../system/string/) | Fjärrvärdens namn. |
| port | **int32_t** | Portnumret för fjärrvärden. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metod


Etablerar en anslutning till den angivna fjärrslutpunkten.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP-adresserna för fjärrvärden. |
| port | **int32_t** | Portnumret för fjärrvärden. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [EndPoint](../../../system.net/endpoint/)
* Klass [Socket](../)
* Klass [IPAddress](../../../system.net/ipaddress/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)