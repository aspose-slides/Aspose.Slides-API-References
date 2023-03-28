---
title: Receive()
second_title: Aspose.Slides for C++ API Reference
description: Receives data from the socket and writes it to the specified byte array.
type: docs
weight: 664
url: /cpp/system.net.sockets/socket/receive/
---
## Socket::Receive([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array where the received data will be assigned. |
| size | **int32_t** | The number of bytes to receive. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The byte array where the received data will be assigned. |
| size | **int32_t** | The number of bytes to receive. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The byte array where the received data will be assigned. |
| size | **int32_t** | The number of bytes to receive. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array where the received data will be assigned. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The byte array where the received data will be assigned. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The byte array where the received data will be assigned. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array where the received data will be assigned. |

### Return Value

The number of received bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::ArrayView\<**uint8_t**\>) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The byte array where the received data will be assigned. |

### Return Value

The number of received bytes.

## See Also

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::StackArray\<**uint8_t**, N\>\&) method


Receives data from the socket and writes it to the specified byte array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The byte array where the received data will be assigned. |

### Return Value

The number of received bytes.

## See Also

* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../../socketflags/), [SocketError](../../socketerror/)\&) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Return Value

The number of received bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../../socketflags/), [SocketError](../../socketerror/)\&) method


Receives data from the socket and writes it to the specified byte array.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../../socketflags/), [SocketError](../../socketerror/)\&) method


Receives data from the socket and writes it to the specified byte array.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The byte array where the received data will be assigned. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes to receive that will be assigned to the specified byte array from the 'offset' index. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behavior. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive([System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\>) method


Receives data from the socket and writes it to the specified byte arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | The byte arrays where the received data will be assigned. |

### Return Value

The number of bytes that are received.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive([System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../../socketflags/)) method


Receives data from the socket and writes it to the specified byte arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | The byte arrays where the received data will be assigned. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behaviour. |

### Return Value

The number of received bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## Socket::Receive([System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../../socketflags/), [SocketError](../../socketerror/)\&) method


Receives data from the socket and writes it to the specified byte arrays.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | The byte arrays where the received data will be assigned. |
| socketFlags | [SocketFlags](../../socketflags/) | The receive behaviour. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Return Value

The number of received bytes.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
