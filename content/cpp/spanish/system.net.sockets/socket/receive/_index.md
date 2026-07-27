---
title: Receive()
second_title: Referencia de API de Aspose.Slides para C++
description: Recibe datos del socket y los escribe en el arreglo de bytes especificado.
type: docs
weight: 664
url: /es/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | **int32_t** | El número de bytes a recibir. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | **int32_t** | El número de bytes a recibir. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| size | **int32_t** | El número de bytes a recibir. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el arreglo especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al arreglo de bytes especificado a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el arreglo especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al arreglo de bytes especificado a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el arreglo especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al arreglo de bytes especificado a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el arreglo especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al arreglo de bytes especificado a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | El arreglo de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el arreglo especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al arreglo de bytes especificado a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) método

Recibe datos del socket y los escribe en el arreglo de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | El arreglo de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en el arreglo especificado. |
| size | **int32_t** | El número de bytes a recibir que se asignarán al arreglo de bytes especificado a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) método

Recibe datos del socket y los escribe en los arreglos de bytes especificados.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Los arreglos de bytes donde se asignarán los datos recibidos. |

### Valor devuelto

El número de bytes que se reciben.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) método

Recibe datos del socket y los escribe en los arreglos de bytes especificados.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Los arreglos de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) método

Recibe datos del socket y los escribe en los arreglos de bytes especificados.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Los arreglos de bytes donde se asignarán los datos recibidos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de recepción. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando falle la operación de recepción. |

### Valor devuelto

El número de bytes recibidos.

## Véase también

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)