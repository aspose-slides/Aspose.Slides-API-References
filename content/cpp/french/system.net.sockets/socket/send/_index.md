---
title: Send()
second_title: Référence API Aspose.Slides pour C++
description: Envoie les données spécifiées au socket.
type: docs
weight: 638
url: /fr/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| size | **int32_t** | Le nombre d'octets des données spécifiées qui doivent être envoyés. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| size | **int32_t** | Le nombre d'octets des données spécifiées qui doivent être envoyés. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| size | **int32_t** | Le nombre d'octets des données spécifiées qui doivent être envoyés. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::ArrayPtr\<uint8_t\>) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method

Envoie les données spécifiées au socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Une collection de tableaux d'octets à partir desquels les données doivent être envoyées. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Une collection de tableaux d'octets à partir desquels les données doivent être envoyées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Une collection de tableaux d'octets à partir desquels les données doivent être envoyées. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération d'envoi échoue. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method

Envoie les données spécifiées au socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération d'envoi échoue. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method

Envoie les données spécifiées au socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération d'envoi échoue. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method

Envoie les données spécifiées au socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Les données à envoyer. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération d'envoi échoue. |

### Valeur de retour

Le nombre d'octets envoyés.

## Voir aussi

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Socket](../)
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [ArraySegment](../../../system/arraysegment/)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)