---
title: ReceiveMessageFrom()
second_title: Référence API Aspose.Slides pour C++
description: Reçoit les données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.
type: docs
weight: 677
url: /fr/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) méthode


Reçoit les données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Le paramètre de sortie où les informations sur le paquet seront assignées. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) méthode


Reçoit les données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Le paramètre de sortie où les informations sur le paquet seront assignées. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) méthode


Reçoit les données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront assignées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Le paramètre de sortie où les informations sur le paquet seront assignées. |

### Valeur de retour

Le nombre d'octets reçus.

## Voir aussi

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)