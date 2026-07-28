---
title: Connect()
second_title: Aspose.Slides C++ API-referencia
description: Kapcsolatot hoz létre a megadott távoli végponton.
type: docs
weight: 560
url: /hu/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) metódus


Kapcsolatot hoz létre a megadott távoli végponton.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | A távoli végpont. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) metódus


Kapcsolatot hoz létre a megadott távoli végponton.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | A távoli gép IP-címe. |
| port | **int32_t** | A távoli gép portszáma. |

## Socket::Connect(String, int32_t) metódus


Kapcsolatot hoz létre a megadott távoli végponton.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | A távoli gép neve. |
| port | **int32_t** | A távoli gép portszáma. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metódus


Kapcsolatot hoz létre a megadott távoli végponton.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | A távoli gép IP-címei. |
| port | **int32_t** | A távoli gép portszáma. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [EndPoint](../../../system.net/endpoint/)
* Osztály [Socket](../)
* Osztály [IPAddress](../../../system.net/ipaddress/)
* Osztály [String](../../../system/string/)
* Névtér [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)