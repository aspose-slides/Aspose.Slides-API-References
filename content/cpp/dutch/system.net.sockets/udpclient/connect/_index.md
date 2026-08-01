---
title: Connect()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een verbinding tot stand met de opgegeven poort op de opgegeven host.
type: docs
weight: 66
url: /nl/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) methode


Stelt een verbinding tot stand met de opgegeven poort op de opgegeven host.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | De naam van de externe DNS-host waarmee u verbinding wilt maken. |
| port | **int32_t** | Het lokale poortnummer vanwaar u wilt communiceren. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) methode


Stelt een verbinding tot stand met de host op het opgegeven adres en de opgegeven poort.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | De [IPAddress](../../../system.net/ipaddress/) van de externe host waarnaar u gegevens wilt verzenden. |
| port | **int32_t** | Het lokale poortnummer vanwaar u wilt communiceren. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) methode


Stelt een verbinding tot stand met een extern eindpunt.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Het eindpunt waaraan u de UDP-verbinding bindt. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [UdpClient](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Naamruimte [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)