---
title: SendTo()
second_title: Référence API Aspose.Slides pour C++
description: Envoie les données spécifiées à l'extrémité spécifiée.
type: docs
weight: 651
url: /fr/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) méthode


Envoie les données spécifiées à l'extrémité spécifiée.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets envoyés.

## Voir aussi

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)