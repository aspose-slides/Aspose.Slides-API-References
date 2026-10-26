---
title: ReceiveFrom()
second_title: Référence de l'API Aspose.Slides pour C++
description: Reçoit les données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.
type: docs
weight: 690
url: /fr/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront assignées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront assignées. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront assignées. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) méthode

Reçoit des données du point de terminaison spécifié et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront assignées. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Le point de terminaison distant. |

### Valeur de retour

Le nombre d'octets reçus.

## Voir aussi

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)