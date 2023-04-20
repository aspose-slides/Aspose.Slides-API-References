---
title: EndReceive()
second_title: Aspose.Slides for C++ API Reference
description: Waits until the specified asynchronous receive operation completes.
type: docs
weight: 534
url: /cpp/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous receive operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |

### Return Value

The number of bytes that are received.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Waits until the specified asynchronous receive operation completes.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous receive operation. |
| errorCode | [SocketError](../../socketerror/)\& | The output parameter where the error code will be assigned when the receive operation fails. |

### Return Value

The number of received bytes.

## See Also

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)