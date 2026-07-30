---
title: Receive()
second_title: Riferimento API di Aspose.Slides per C++
description: Riceve i dati dal socket e li scrive nell'array di byte specificato.
type: docs
weight: 664
url: /it/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| size | **int32_t** | Il numero di byte da ricevere. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| size | **int32_t** | Il numero di byte da ricevere. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte dove verranno assegnati i dati ricevuti. |
| size | **int32_t** | Il numero di byte da ricevere. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte dove verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte dove verranno assegnati i dati ricevuti. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato a partire dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato a partire dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato a partire dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato a partire dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di ricezione fallisce. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato a partire dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di ricezione fallisce. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) metodo


Riceve i dati dal socket e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte dove verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato a partire dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di ricezione fallisce. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) metodo


Riceve i dati dal socket e li scrive negli array di byte specificati.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Gli array di byte dove verranno assegnati i dati ricevuti. |

### Valore di ritorno

Il numero di byte che sono ricevuti.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) metodo


Riceve i dati dal socket e li scrive negli array di byte specificati.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Gli array di byte dove verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) metodo


Riceve i dati dal socket e li scrive negli array di byte specificati.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Gli array di byte dove verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output dove verrà assegnato il codice di errore quando l'operazione di ricezione fallisce. |

### Valore di ritorno

Il numero di byte ricevuti.

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