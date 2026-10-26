---
title: Send()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odesílá UDP datagram na hostitele na vzdáleném koncovém bodě.
type: docs
weight: 79
url: /cs/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) metoda

Odesílá UDP datagram na hostitele na vzdáleném koncovém bodě.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole typu [Byte](../../../system/byte/) k odeslání |
| bytes | **int32_t** | Počet bytů v datagramu. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Objekt [IPEndPoint](../../../system.net/ipendpoint/) představuje hostitele a port, na který se má datagram odeslat. |

### Návratová hodnota

Počet odeslaných bytů.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) metoda

Odesílá UDP datagram na určený port na specifikovaném vzdáleném hostiteli.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole typu [Byte](../../../system/byte/) k odeslání |
| bytes | **int32_t** | Počet bytů v datagramu. |
| hostname | [String](../../../system/string/) | Název vzdáleného hostitele. |
| port | **int32_t** | Číslo vzdáleného portu. |

### Návratová hodnota

Počet odeslaných bytů.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) metoda

Odesílá UDP datagram na vzdálený hostitel.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole typu [Byte](../../../system/byte/) k odeslání. |
| bytes | **int32_t** | Počet bytů v datagramu. |

### Návratová hodnota

Počet odeslaných bytů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPEndPoint](../../../system.net/ipendpoint/)
* Třída [UdpClient](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)