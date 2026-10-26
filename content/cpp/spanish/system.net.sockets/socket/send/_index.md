---
title: Send()
second_title: Referencia de API de Aspose.Slides para C++
description: Envía los datos especificados al socket.
type: docs
weight: 638
url: /es/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| size | **int32_t** | El número de bytes de los datos especificados que deben enviarse. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| size | **int32_t** | El número de bytes de los datos especificados que deben enviarse. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| size | **int32_t** | El número de bytes de los datos especificados que deben enviarse. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Una colección de matrices de bytes de los que se deben enviar datos. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Una colección de matrices de bytes de los que se deben enviar datos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Una colección de matrices de bytes de los que se deben enviar datos. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes dentro de la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada a partir del parámetro ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes dentro de la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada a partir del parámetro ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes dentro de la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada a partir del parámetro ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes dentro de la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada a partir del parámetro ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes dentro de la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada a partir del parámetro ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### Valor devuelto

El número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Envía los datos especificados al socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes dentro de la matriz especificada. |
| size | **int32_t** | El número de bytes en la matriz especificada a partir del parámetro ‘offset’. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| errorCode | [SocketError](../../socketerror/)\& | El parámetro de salida donde se asignará el código de error cuando la operación de envío falle. |

### Valor devuelto

El número de bytes enviados.

## Ver también

* Enumeración [SocketFlags](../../socketflags/)
* Enumeración [SocketError](../../socketerror/)
* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [Socket](../)
* Clase [IList](../../../system.collections.generic/ilist/)
* Clase [ArraySegment](../../../system/arraysegment/)
* Espacio de nombres [System::Net::Sockets](../../)
* Biblioteca [Aspose.Slides](../../../)