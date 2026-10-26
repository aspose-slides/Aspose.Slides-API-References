---
title: Send()
second_title: Aspose.Slides voor C++ API-referentie
description: Verstuurt een UDP-datagram naar de host op het externe eindpunt.
type: docs
weight: 79
url: /nl/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) methode


Verstuurt een UDP-datagram naar de host op het externe eindpunt.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Een array van type [Byte](../../../system/byte/) om te verzenden |
| bytes | **int32_t** | Het aantal bytes in het datagram. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Een [IPEndPoint](../../../system.net/ipendpoint/) die de host en poort vertegenwoordigt waar het datagram naartoe moet worden verzonden. |

### Retourwaarde

Het aantal bytes dat is verzonden.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) methode


Verstuurt een UDP-datagram naar de opgegeven poort op de opgegeven externe host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Een array van type [Byte](../../../system/byte/) om te verzenden |
| bytes | **int32_t** | Het aantal bytes in het datagram. |
| hostname | [String](../../../system/string/) | Een naam van de externe host. |
| port | **int32_t** | Een extern poortnummer. |

### Retourwaarde

Het aantal bytes dat is verzonden.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) methode


Verstuurt een UDP-datagram naar een externe host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Een array van type [Byte](../../../system/byte/) om te verzenden. |
| bytes | **int32_t** | Het aantal bytes in het datagram. |

### Retourwaarde

Het aantal bytes dat is verzonden.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [UdpClient](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)