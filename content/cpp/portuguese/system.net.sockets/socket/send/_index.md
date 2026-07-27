---
title: Send()
second_title: Referência da API Aspose.Slides for C++
description: Envia os dados especificados ao socket.
type: docs
weight: 638
url: /pt/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Os dados a serem enviados. |
| size | **int32_t** | O número de bytes dos dados especificados que devem ser enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Os dados a serem enviados. |
| size | **int32_t** | O número de bytes dos dados especificados que devem ser enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Os dados a serem enviados. |
| size | **int32_t** | O número de bytes dos dados especificados que devem ser enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Os dados a serem enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Os dados a serem enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Os dados a serem enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Os dados a serem enviados. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Os dados a serem enviados. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) método


Envia os dados especificados ao socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Os dados a serem enviados. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Uma coleção de arrays de bytes dos quais os dados devem ser enviados. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Uma coleção de arrays de bytes dos quais os dados devem ser enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Uma coleção de arrays de bytes dos quais os dados devem ser enviados. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |
| errorCode | [SocketError](../../socketerror/)\& | Um parâmetro de saída onde o código de erro será atribuído quando a operação de envio falhar. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Os dados a serem enviados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes no array especificado a partir do parâmetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Os dados a serem enviados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes no array especificado a partir do parâmetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) método


Envia os dados especificados ao socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Os dados a serem enviados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes no array especificado a partir do parâmetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Os dados a serem enviados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes no array especificado a partir do parâmetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |
| errorCode | [SocketError](../../socketerror/)\& | Um parâmetro de saída onde o código de erro será atribuído quando a operação de envio falhar. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) método


Envia os dados especificados ao socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Os dados a serem enviados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes no array especificado a partir do parâmetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |
| errorCode | [SocketError](../../socketerror/)\& | Um parâmetro de saída onde o código de erro será atribuído quando a operação de envio falhar. |

### Valor de Retorno

O número de bytes enviados.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) método


Envia os dados especificados ao socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Os dados a serem enviados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes no array especificado a partir do parâmetro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de envio. |
| errorCode | [SocketError](../../socketerror/)\& | Um parâmetro de saída onde o código de erro será atribuído quando a operação de envio falhar. |

### Valor de Retorno

O número de bytes enviados.

## Veja Também

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [Socket](../)
* classe [IList](../../../system.collections.generic/ilist/)
* classe [ArraySegment](../../../system/arraysegment/)
* espaço de nomes [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)