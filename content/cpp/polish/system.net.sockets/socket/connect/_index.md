---
title: Connect()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Nawiązuje połączenie do określonego zdalnego punktu końcowego.
type: docs
weight: 560
url: /pl/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) metoda


Nawiązuje połączenie do określonego zdalnego punktu końcowego.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Zdalny punkt końcowy. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) metoda


Nawiązuje połączenie do określonego zdalnego punktu końcowego.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Adres IP zdalnego hosta. |
| port | **int32_t** | Numer portu zdalnego hosta. |

## Socket::Connect(String, int32_t) metoda


Nawiązuje połączenie do określonego zdalnego punktu końcowego.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nazwa zdalnego hosta. |
| port | **int32_t** | Numer portu zdalnego hosta. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metoda


Nawiązuje połączenie do określonego zdalnego punktu końcowego.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Adresy IP zdalnego hosta. |
| port | **int32_t** | Numer portu zdalnego hosta. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [EndPoint](../../../system.net/endpoint/)
* Klasa [Socket](../)
* Klasa [IPAddress](../../../system.net/ipaddress/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)