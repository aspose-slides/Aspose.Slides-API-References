---
title: EndRead()
second_title: Aspose.Slides for C++ API Reference
description: Waits until the specified asynchronous read operation completes.
type: docs
weight: 261
url: /cpp/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous read operation completes.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous read operation |

### Return Value

The number of bytes read during the read operation represented by **asyncResult**

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)