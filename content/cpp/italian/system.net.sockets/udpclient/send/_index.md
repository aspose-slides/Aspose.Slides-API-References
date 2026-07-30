---
title: Send()
second_title: Riferimento API di Aspose.Slides per C++
description: Invia un datagramma UDP all'host al punto finale remoto.
type: docs
weight: 79
url: /it/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) metodo

Invia un datagramma UDP all'host al punto finale remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un array di tipo [Byte](../../../system/byte/) da inviare |
| bytes | **int32_t** | Il numero di byte nel datagramma. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Un [IPEndPoint](../../../system.net/ipendpoint/) che rappresenta l'host e la porta a cui inviare il datagramma. |

### Valore di ritorno

Il numero di byte che sono stati inviati.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) metodo

Invia un datagramma UDP alla porta specificata sull'host remoto specificato.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un array di tipo [Byte](../../../system/byte/) da inviare |
| bytes | **int32_t** | Il numero di byte nel datagramma. |
| hostname | [String](../../../system/string/) | Un nome dell'host remoto. |
| port | **int32_t** | Un numero di porta remota. |

### Valore di ritorno

Il numero di byte che sono stati inviati.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) metodo

Invia un datagramma UDP a un host remoto.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un array di tipo [Byte](../../../system/byte/) da inviare. |
| bytes | **int32_t** | Il numero di byte nel datagramma. |

### Valore di ritorno

Il numero di byte che sono stati inviati.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)