---
title: ReceiveMessageFrom()
second_title: Aspose.Slides for C++ API Reference
description: Receives data from the specified endpoint and writes it to the specified byte array.
type: docs
weight: 677
url: /system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Receives data from the specified endpoint and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/)\& | The receive behavior. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | The remote endpoint. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | The output parameter where information about the packet will be assigned. |

### Return Value

The number of received bytes.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Receives data from the specified endpoint and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/)\& | The receive behavior. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | The remote endpoint. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | The output parameter where information about the packet will be assigned. |

### Return Value

The number of received bytes.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method


Receives data from the specified endpoint and writes it to the specified byte array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/)\& | The receive behavior. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | The remote endpoint. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | The output parameter where information about the packet will be assigned. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)