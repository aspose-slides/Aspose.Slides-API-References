---
title: Connect()
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt een verbinding tot stand met het opgegeven externe eindpunt.
type: docs
weight: 560
url: /nl/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) methode


Stelt een verbinding tot stand met het opgegeven externe eindpunt.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Het externe eindpunt. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) methode


Stelt een verbinding tot stand met het opgegeven externe eindpunt.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Het IP-adres van de externe host. |
| port | **int32_t** | Het poortnummer van de externe host. |

## Socket::Connect(String, int32_t) methode


Stelt een verbinding tot stand met het opgegeven externe eindpunt.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | [String](../../../system/string/) | De hostnaam van de externe host. |
| port | **int32_t** | Het poortnummer van de externe host. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) methode


Stelt een verbinding tot stand met het opgegeven externe eindpunt.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | De IP-adressen van de externe host. |
| port | **int32_t** | Het poortnummer van de externe host. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [EndPoint](../../../system.net/endpoint/)
* Klasse [Socket](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)