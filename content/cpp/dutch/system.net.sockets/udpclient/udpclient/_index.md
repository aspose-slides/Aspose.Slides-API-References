---
title: UdpClient()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de UdpClient klasse.
type: docs
weight: 27
url: /nl/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() constructor


Initialiseert een nieuw exemplaar van de [UdpClient](../) klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) constructor


Initialiseert een nieuw exemplaar van de [UdpClient](../) klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | waarde die het adresseringsschema van de socket specificeert. |

## UdpClient::UdpClient(int32_t) constructor


Initialiseert een nieuw exemplaar van de [UdpClient](../) klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| port | **int32_t** | het lokale poortnummer vanwaar u wilt communiceren. |

## UdpClient::UdpClient(int32_t, AddressFamily) constructor


Initialiseert een nieuw exemplaar van de [UdpClient](../) klasse.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| port | **int32_t** | het lokale poortnummer vanwaar u wilt communiceren. |
| family | [AddressFamily](../../addressfamily/) | waarde die het adresseringsschema van de socket specificeert. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) constructor


Initialiseert een nieuw exemplaar van de [UdpClient](../) klasse. param local EP het lokale eindpunt waaraan u de UDP-verbinding bindt.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) constructor


Maakt een nieuw exemplaar van de [UdpClient](../) klasse en maakt verbinding met de opgegeven externe host op de opgegeven poort.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | De naam van de externe DNS-host waarmee u verbinding wilt maken. |
| port | **int32_t** | Het lokale poortnummer vanwaar u wilt communiceren. |

## Zie Ook

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [UdpClient](../)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)