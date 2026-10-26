---
title: Send()
second_title: Aspose.Slides C++ API Referencia
description: UDP-datagramot küld a távoli végpontban lévő hosztra.
type: docs
weight: 79
url: /hu/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method

UDP-datagramot küld a távoli végpontban lévő hosztra.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő [Byte](../../../system/byte/) típusú tömb |
| bytes | **int32_t** | A datagram mérete bájtokban. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Egy [IPEndPoint](../../../system.net/ipendpoint/), amely a hostot és a portot képviseli, ahová a datagramot el kell küldeni. |

### Visszatérési érték

A küldött bájtok száma.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method

UDP-datagramot küld a megadott távoli kiszolgálón a megadott portra.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő [Byte](../../../system/byte/) típusú tömb |
| bytes | **int32_t** | A datagram mérete bájtokban. |
| hostname | [String](../../../system/string/) | A távoli kiszolgáló neve. |
| port | **int32_t** | A távoli port száma. |

### Visszatérési érték

A küldött bájtok száma.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method

UDP-datagramot küld egy távoli kiszolgálónak.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az elküldendő [Byte](../../../system/byte/) típusú tömb. |
| bytes | **int32_t** | A datagram mérete bájtokban. |

### Visszatérési érték

A küldött bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)