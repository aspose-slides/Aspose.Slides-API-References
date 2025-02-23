---
title: Send()
second_title: Aspose.Slides for C++ API Reference
description: Sends the specified data to the socket.
type: docs
weight: 638
url: /system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The data to send. |
| size | **int32_t** | The number of bytes from the specified data that must be send. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The data to send. |
| size | **int32_t** | The number of bytes from the specified data that must be send. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The data to send. |
| size | **int32_t** | The number of bytes from the specified data that must be send. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The data to send. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The data to send. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The data to send. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The data to send. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The data to send. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The data to send. |

### Return Value

The number of sent bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | A collection of byte arrays from which data must be sent. |

### Return Value

The number of sent bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | A collection of byte arrays from which data must be sent. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | A collection of byte arrays from which data must be sent. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the send operation fails. |

### Return Value

The number of sent bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The data to send. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The data to send. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The data to send. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |

### Return Value

The number of sent bytes.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The data to send. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the send operation fails. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | The data to send. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the send operation fails. |

### Return Value

The number of sent bytes.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


Sends the specified data to the socket.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | The data to send. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behavior. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the send operation fails. |

### Return Value

The number of sent bytes.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)