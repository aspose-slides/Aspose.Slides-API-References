---
title: ReceiveMessageFrom()
second_title: Aspose.Slides för C++ API-referens
description: Tar emot data från den specificerade slutpunkten och skriver dem till den specificerade bytearrayen.
type: docs
weight: 677
url: /sv/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metod


Tar emot data från den specificerade slutpunkten och skriver dem till den specificerade bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen där mottagna data kommer att tilldelas. |
| offset | **int32_t** | Förskjutningen i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte att ta emot som kommer att tilldelas den specificerade bytearrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärrslutpunkten. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Utdata-parameter där information om paketet kommer att tilldelas. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metod


Tar emot data från den specificerade slutpunkten och skriver dem till den specificerade bytearrayen.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | Bytearrayen där mottagna data kommer att tilldelas. |
| offset | **int32_t** | Förskjutningen i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte att ta emot som kommer att tilldelas den specificerade bytearrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärrslutpunkten. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Utdata-parameter där information om paketet kommer att tilldelas. |

### Returvärde

Antalet mottagna byte.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) metod


Tar emot data från den specificerade slutpunkten och skriver dem till den specificerade bytearrayen.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | Bytearrayen där mottagna data kommer att tilldelas. |
| offset | **int32_t** | Förskjutningen i byte i den specificerade arrayen. |
| size | **int32_t** | Antalet byte att ta emot som kommer att tilldelas den specificerade bytearrayen från 'offset'-indexet. |
| socketFlags | [SocketFlags](../../socketflags/)\& | Mottagningsbeteendet. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | Den fjärrslutpunkten. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | Utdata-parameter där information om paketet kommer att tilldelas. |

### Returvärde

Antalet mottagna byte.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [EndPoint](../../../system.net/endpoint/)
* klass [IPPacketInformation](../../ippacketinformation/)
* klass [Socket](../)
* namnrymd [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)