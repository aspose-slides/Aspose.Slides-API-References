---
title: ReceiveFrom()
second_title: Referencia de la API de Aspose.Slides para C++
description: Recibe datos del punto final especificado y los escribe en el array de bytes especificado.
type: docs
weight: 690
url: /es/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al array de bytes especificado desde el índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al array de bytes especificado desde el índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El array de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al array de bytes especificado desde el índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al array de bytes especificado desde el índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al array de bytes especificado desde el índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El array de bytes donde se asignarán los datos recibidos. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al array de bytes especificado desde el índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El array de bytes donde se asignarán los datos recibidos. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) método


Recibe datos del punto final especificado y los escribe en el array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El array de bytes donde se asignarán los datos recibidos. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |

### Valor de retorno

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [EndPoint](../../../system.net/endpoint/)
* Clase [Socket](../)
* Espacio de nombres [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)