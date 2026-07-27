---
title: SendTo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Envía los datos especificados al punto de conexión especificado.
type: docs
weight: 651
url: /es/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de bytes en el array especificado a partir del parámetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de bytes en el array especificado a partir del parámetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| offset | **int32_t** | El desplazamiento en bytes en el array especificado. |
| size | **int32_t** | El número de bytes en el array especificado a partir del parámetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| size | **int32_t** | El número de bytes en el array especificado. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| size | **int32_t** | El número de bytes en el array especificado. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| size | **int32_t** | El número de bytes en el array especificado. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| socketFlags | [SocketFlags](../../socketflags/) | El comportamiento de envío. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Los datos a enviar. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Los datos a enviar. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) method


Envía los datos especificados al punto de conexión especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Los datos a enviar. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | El punto de conexión remoto. |

### Valor devuelto

El número de bytes enviados.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)