---
title: ReceiveFrom()
second_title: Referência da API Aspose.Slides para C++
description: Recebe dados do endpoint especificado e grava-os no array de bytes especificado.
type: docs
weight: 690
url: /pt/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| size | **int32_t** | O número de bytes a receber que serão atribuídos ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| socketFlags | [SocketFlags](../../socketflags/) | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method

Recebe dados do endpoint especificado e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O endpoint remoto. |

### Valor de retorno

O número de bytes recebidos.

## Veja também

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [EndPoint](../../../system.net/endpoint/)
* Classe [Socket](../)
* Espaço de nomes [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)