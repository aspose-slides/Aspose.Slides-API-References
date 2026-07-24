---
title: Send()
second_title: Aspose.Slides für C++ API Referenz
description: Sendet ein UDP-Datagramm an den Host am entfernten Endpunkt.
type: docs
weight: 79
url: /de/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) Methode

Sendet ein UDP-Datagramm an den Host am entfernten Endpunkt.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ein Array vom Typ [Byte](../../../system/byte/) zum Senden |
| bytes | **int32_t** | Die Anzahl der Bytes im Datagramm. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Ein [IPEndPoint](../../../system.net/ipendpoint/), das den Host und Port repräsentiert, an den das Datagramm gesendet werden soll. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) Methode

Sendet ein UDP-Datagramm an den angegebenen Port auf dem angegebenen entfernten Host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ein Array vom Typ [Byte](../../../system/byte/) zum Senden |
| bytes | **int32_t** | Die Anzahl der Bytes im Datagramm. |
| hostname | [String](../../../system/string/) | Ein Name des entfernten Hosts. |
| port | **int32_t** | Eine entfernte Portnummer. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) Methode

Sendet ein UDP-Datagramm an einen entfernten Host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ein Array vom Typ [Byte](../../../system/byte/) zum Senden. |
| bytes | **int32_t** | Die Anzahl der Bytes im Datagramm. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Klasse [UdpClient](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)