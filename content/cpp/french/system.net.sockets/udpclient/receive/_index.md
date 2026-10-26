---
title: Receive()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Renvoie un datagramme envoyé par un serveur.
type: docs
weight: 92
url: /fr/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) méthode

Renvoie un datagramme envoyé par un serveur.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Un [IPEndPoint](../../../system.net/ipendpoint/) qui représente l'hôte distant depuis lequel les données ont été envoyées. |

### Valeur de retour

Un tableau d'octets où les données reçues seront assignées.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [UdpClient](../)
* Espace de noms [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)