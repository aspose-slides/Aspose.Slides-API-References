---
title: Send()
second_title: Riferimento API Aspose.Slides per C++
description: Invia i dati specificati al socket.
type: docs
weight: 638
url: /it/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | I dati da inviare. |
| size | **int32_t** | Il numero di byte dei dati specificati che devono essere inviati. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | I dati da inviare. |
| size | **int32_t** | Il numero di byte dei dati specificati che devono essere inviati. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | I dati da inviare. |
| size | **int32_t** | Il numero di byte dei dati specificati che devono essere inviati. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | I dati da inviare. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | I dati da inviare. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | I dati da inviare. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::ArrayPtr\<uint8_t\>) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | I dati da inviare. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | I dati da inviare. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) metodo


Invia i dati specificati al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | I dati da inviare. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Una raccolta di array di byte da cui i dati devono essere inviati. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Una raccolta di array di byte da cui i dati devono essere inviati. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Una raccolta di array di byte da cui i dati devono essere inviati. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di invio fallisce. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | I dati da inviare. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte nell'array specificato a partire dal parametro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | I dati da inviare. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte nell'array specificato a partire dal parametro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metodo


Invia i dati specificati al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | I dati da inviare. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte nell'array specificato a partire dal parametro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | I dati da inviare. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte nell'array specificato a partire dal parametro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di invio fallisce. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metodo


Invia i dati specificati al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | I dati da inviare. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte nell'array specificato a partire dal parametro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di invio fallisce. |

### Valore restituito

Il numero di byte inviati.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metodo


Invia i dati specificati al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | I dati da inviare. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte nell'array specificato a partire dal parametro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di invio fallisce. |

### Valore restituito

Il numero di byte inviati.

## Vedi anche

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)