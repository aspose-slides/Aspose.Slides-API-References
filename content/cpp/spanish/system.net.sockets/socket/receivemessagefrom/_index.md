---
title: ReceiveMessageFrom()
second_title: Referencia de API de Aspose.Slides para C++
description: Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.
type: docs
weight: 677
url: /es/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | La matriz de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| size | **int32_t** | El número de bytes a recibir que se asignarán a la matriz de bytes especificada a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | El parámetro de salida donde se asignará la información del paquete. |

### Valor devuelto

El número de bytes recibidos.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | La matriz de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| size | **int32_t** | El número de bytes a recibir que se asignarán a la matriz de bytes especificada a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | El parámetro de salida donde se asignará la información del paquete. |

### Valor devuelto

El número de bytes recibidos.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

Recibe datos del punto final especificado y los escribe en la matriz de bytes especificada.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | La matriz de bytes donde se asignarán los datos recibidos. |
| offset | **int32_t** | El desplazamiento en bytes en la matriz especificada. |
| size | **int32_t** | El número de bytes a recibir que se asignarán a la matriz de bytes especificada a partir del índice 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | El comportamiento de recepción. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | El punto final remoto. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | El parámetro de salida donde se asignará la información del paquete. |

### Valor devuelto

El número de bytes recibidos.

## Ver también

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)