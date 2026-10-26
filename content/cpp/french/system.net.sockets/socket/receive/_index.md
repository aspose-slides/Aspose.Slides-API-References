---
title: Receive()
second_title: Référence de l'API Aspose.Slides pour C++
description: Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.
type: docs
weight: 664
url: /fr/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| size | **int32_t** | Le nombre d'octets à recevoir. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| size | **int32_t** | Le nombre d'octets à recevoir. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront affectées. |
| size | **int32_t** | Le nombre d'octets à recevoir. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront affectées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront affectées. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront affectées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération de réception échoue. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Le tableau d'octets où les données reçues seront affectées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération de réception échoue. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method

Reçoit des données du socket et les écrit dans le tableau d'octets spécifié.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Le tableau d'octets où les données reçues seront affectées. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à recevoir qui seront assignés au tableau d'octets spécifié à partir de l'index 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération de réception échoue. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method

Reçoit des données du socket et les écrit dans les tableaux d'octets spécifiés.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Les tableaux d'octets où les données reçues seront affectées. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method

Reçoit des données du socket et les écrit dans les tableaux d'octets spécifiés.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Les tableaux d'octets où les données reçues seront affectées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method

Reçoit des données du socket et les écrit dans les tableaux d'octets spécifiés.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Les tableaux d'octets où les données reçues seront affectées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement de réception. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération de réception échoue. |

### Valeur de retour

Le nombre d'octets reçus.

## Voir aussi

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)