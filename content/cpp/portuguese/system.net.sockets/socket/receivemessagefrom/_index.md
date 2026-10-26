---
title: ReceiveMessageFrom()
second_title: Referência da API Aspose.Slides para C++
description: Recebe dados do ponto de extremidade especificado e grava-os no array de bytes especificado.
type: docs
weight: 677
url: /pt/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) método


Recebe dados do ponto de extremidade especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que será atribuído ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O ponto de extremidade remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | O parâmetro de saída onde as informações sobre o pacote serão atribuídas. |

### Valor de Retorno

O número de bytes recebidos.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) método


Recebe dados do ponto de extremidade especificado e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que será atribuído ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O ponto de extremidade remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | O parâmetro de saída onde as informações sobre o pacote serão atribuídas. |

### Valor de Retorno

O número de bytes recebidos.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) método


Recebe dados do ponto de extremidade especificado e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | O array de bytes onde os dados recebidos serão atribuídos. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a receber que será atribuído ao array de bytes especificado a partir do índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | O comportamento de recebimento. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | O ponto de extremidade remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | O parâmetro de saída onde as informações sobre o pacote serão atribuídas. |

### Valor de Retorno

O número de bytes recebidos.

## Veja Também

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)