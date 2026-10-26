---
title: Connect()
second_title: Référence API Aspose.Slides pour C++
description: Établit une connexion au port spécifié sur l'hôte spécifié.
type: docs
weight: 66
url: /fr/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) méthode

Établit une connexion au port spécifié sur l'hôte spécifié.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Le nom de l'hôte DNS distant auquel vous souhaitez vous connecter. |
| port | **int32_t** | Le numéro de port local à partir duquel vous avez l'intention de communiquer. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) méthode

Établit une connexion avec l'hôte à l'adresse spécifiée sur le port spécifié.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Le [IPAddress](../../../system.net/ipaddress/) de l'hôte distant auquel envoyer des données. |
| port | **int32_t** | Le numéro de port local à partir duquel vous avez l'intention de communiquer. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) méthode

Établit une connexion à un point d'extrémité distant.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | le point d'extrémité auquel vous liez la connexion UDP. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [UdpClient](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)