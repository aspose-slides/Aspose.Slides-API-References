---
title: Send()
second_title: Aspose.Slides för C++ API-referens
description: Skickar ett UDP-datagram till värden på den fjärranslutna slutpunkten.
type: docs
weight: 79
url: /sv/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) metod


Skickar ett UDP-datagram till värden på den fjärranslutna slutpunkten.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En array av typen [Byte](../../../system/byte/) att skicka |
| bytes | **int32_t** | Antalet byte i datagrammet. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Ett [IPEndPoint](../../../system.net/ipendpoint/) som representerar värden och porten som datagrammet ska skickas till. |

### Returvärde

Antalet byte som skickas.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) metod


Skickar ett UDP-datagram till den angivna porten på den angivna fjärrvärden.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En array av typen [Byte](../../../system/byte/) att skicka |
| bytes | **int32_t** | Antalet byte i datagrammet. |
| hostname | [String](../../../system/string/) | Ett namn på den fjärranslutna värden. |
| port | **int32_t** | Ett fjärrportnummer. |

### Returvärde

Antalet byte som skickas.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) metod


Skickar ett UDP-datagram till en fjärrvärd.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En array av typen [Byte](../../../system/byte/) att skicka. |
| bytes | **int32_t** | Antalet byte i datagrammet. |

### Returvärde

Antalet byte som skickas.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPEndPoint](../../../system.net/ipendpoint/)
* Klass [UdpClient](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)