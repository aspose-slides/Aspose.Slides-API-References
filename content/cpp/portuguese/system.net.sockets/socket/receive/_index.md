---
title: Receive()
second_title: Referência da API Aspose.Slides para C++
description: Recebe dados do socket e grava-os no array de bytes especificado.
type: docs
weight: 664
url: /pt/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| size | **int32_t** | O número de bytes a receber. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| size | **int32_t** | O número de bytes a receber. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| size | **int32_t** | O número de bytes a receber. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| errorCode | [SocketError](../../socketerror/)\& | O parâmetro de saída onde o código de erro será atribuído quando a operação de recepção falhar. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| errorCode | [SocketError](../../socketerror/)\& | O parâmetro de saída onde o código de erro será atribuído quando a operação de recepção falhar. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) método


Recebe dados do socket e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| errorCode | [SocketError](../../socketerror/)\& | O parâmetro de saída onde o código de erro será atribuído quando a operação de recepção falhar. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) método


Recebe dados do socket e grava-os nos arrays de bytes especificados.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Os arrays de bytes onde os dados recebidos serão atribuídos. |

### Valor de retorno

O número de bytes que são recebidos.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) método


Recebe dados do socket e grava-os nos arrays de bytes especificados.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Os arrays de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recepção. |

### Valor de retorno

O número de bytes recebidos.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) método


Recebe dados do socket e grava-os nos arrays de bytes especificados.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | Os arrays de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recepção. |
| errorCode | [SocketError](../../socketerror/)\& | O parâmetro de saída onde o código de erro será atribuído quando a operação de recepção falhar. |

### Valor de retorno

O número de bytes recebidos.

## Veja também

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)