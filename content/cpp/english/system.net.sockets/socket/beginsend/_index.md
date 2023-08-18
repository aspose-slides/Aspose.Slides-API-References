---
title: BeginSend()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous send operation.
type: docs
weight: 495
url: /system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous send operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A buffer to read data from. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| size | **int32_t** | The number of bytes in the specified array starting from the 'offset' parameter. |
| socketFlags | [SocketFlags](../../socketflags/) | The send behaviour. |
| callback | [AsyncCallback](../../../system/asynccallback/) | A callback that will be called when the operation completes. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous send operation. |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous send operation.

## See Also

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)