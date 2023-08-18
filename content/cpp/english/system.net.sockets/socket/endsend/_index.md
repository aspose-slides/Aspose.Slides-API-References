---
title: EndSend()
second_title: Aspose.Slides for C++ API Reference
description: Waits until the specified asynchronous send operation completes.
type: docs
weight: 508
url: /system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous send operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous send operation. |

### Return Value

The number of sent bytes.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Waits until the specified asynchronous send operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous send operation. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the send operation fails. |

### Return Value

The number of sent bytes.

## See Also

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)