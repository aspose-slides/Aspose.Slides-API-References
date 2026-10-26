---
title: Send()
second_title: Référence de l'API Aspose.Slides pour C++
description: Envoie un datagramme UDP à l'hôte du point de terminaison distant.
type: docs
weight: 79
url: /fr/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method

Envoie un datagramme UDP à l’hôte du point de terminaison distant.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un tableau du type [Byte](../../../system/byte/) à envoyer |
| bytes | **int32_t** | Le nombre d’octets dans le datagramme. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Un [IPEndPoint](../../../system.net/ipendpoint/) qui représente l’hôte et le port vers lesquels envoyer le datagramme. |

### Valeur de retour

Le nombre d’octets envoyés.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method

Envoie un datagramme UDP au port spécifié sur l’hôte distant spécifié.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un tableau du type [Byte](../../../system/byte/) à envoyer |
| bytes | **int32_t** | Le nombre d’octets dans le datagramme. |
| hostname | [String](../../../system/string/) | Un nom de l’hôte distant. |
| port | **int32_t** | Un numéro de port distant. |

### Valeur de retour

Le nombre d’octets envoyés.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method

Envoie un datagramme UDP à un hôte distant.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un tableau du type [Byte](../../../system/byte/) à envoyer. |
| bytes | **int32_t** | Le nombre d’octets dans le datagramme. |

### Valeur de retour

Le nombre d’octets envoyés.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IPEndPoint](../../../system.net/ipendpoint/)
* classe [UdpClient](../)
* classe [String](../../../system/string/)
* espace de noms [System::Net::Sockets](../../)
* bibliothèque [Aspose.Slides](../../../)