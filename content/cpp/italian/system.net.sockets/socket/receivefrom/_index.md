---
title: ReceiveFrom()
second_title: Riferimento API di Aspose.Slides per C++
description: Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.
type: docs
weight: 690
url: /it/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte in cui verranno assegnati i dati ricevuti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte in cui verranno assegnati i dati ricevuti. |
| size | **int32_t** | Il numero di byte da ricevere che verrà assegnato all'array di byte specificato dall'indice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di ricezione. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | L'array di byte in cui verranno assegnati i dati ricevuti. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) metodo


Riceve dati dal endpoint specificato e li scrive nell'array di byte specificato.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | L'array di byte in cui verranno assegnati i dati ricevuti. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | L'endpoint remoto. |

### Valore di ritorno

Il numero di byte ricevuti.

## Vedi anche

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)