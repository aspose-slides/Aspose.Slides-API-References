---
title: Connect()
second_title: Référence API Aspose.Slides pour C++
description: Établit une connexion à l'hôte distant spécifié.
type: docs
weight: 248
url: /fr/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) méthode

Établit une connexion à l'hôte distant spécifié.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Un nom d'hôte distant à connecter. |
| port | **int32_t** | Un port de l'hôte distant à connecter. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) méthode

Établit une connexion à l'hôte distant spécifié.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'adresse IP d'un hôte distant. |
| port | **int32_t** | Un port de l'hôte distant à connecter. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) méthode

Établit une connexion à l'hôte distant spécifié.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Un hôte distant à connecter. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) méthode

Établit une connexion à l'hôte distant spécifié.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Les adresses IP d'un hôte distant. |
| port | **int32_t** | Un port de l'hôte distant à connecter. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [TcpClient](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Espace de noms [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)