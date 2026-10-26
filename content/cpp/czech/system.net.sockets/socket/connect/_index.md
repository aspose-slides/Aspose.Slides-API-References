---
title: Connect()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Navazuje spojení se zadaným vzdáleným koncovým bodem.
type: docs
weight: 560
url: /cs/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) metoda


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Vzdálený koncový bod. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) metoda


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP adresa vzdáleného hostitele. |
| port | **int32_t** | Číslo portu vzdáleného hostitele. |

## Socket::Connect(String, int32_t) metoda


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Název vzdáleného hostitele. |
| port | **int32_t** | Číslo portu vzdáleného hostitele. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metoda


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP adresy vzdáleného hostitele. |
| port | **int32_t** | Číslo portu vzdáleného hostitele. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [EndPoint](../../../system.net/endpoint/)
* Třída [Socket](../)
* Třída [IPAddress](../../../system.net/ipaddress/)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)