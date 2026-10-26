---
title: Connect()
second_title: Référence de l'API Aspose.Slides pour C++
description: Établit une connexion au point de terminaison distant spécifié.
type: docs
weight: 560
url: /fr/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) méthode


Établit une connexion au point de terminaison distant spécifié.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) méthode


Établit une connexion au point de terminaison distant spécifié.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L’adresse IP de l’hôte distant. |
| port | **int32_t** | Le numéro de port de l’hôte distant. |

## Socket::Connect(String, int32_t) méthode


Établit une connexion au point de terminaison distant spécifié.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Le nom de l’hôte distant. |
| port | **int32_t** | Le numéro de port de l’hôte distant. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) méthode


Établit une connexion au point de terminaison distant spécifié.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Les adresses IP de l’hôte distant. |
| port | **int32_t** | Le numéro de port de l’hôte distant. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [EndPoint](../../../system.net/endpoint/)
* Classe [Socket](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)