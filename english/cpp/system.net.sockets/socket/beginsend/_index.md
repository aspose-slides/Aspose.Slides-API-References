---
title: BeginSend()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous send operation.
type: docs
weight: 495
url: /cpp/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../../socketflags/), [AsyncCallback](../../../system/asynccallback/), [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>) method


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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [SocketFlags](../../socketflags/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
