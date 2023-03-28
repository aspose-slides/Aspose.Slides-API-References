---
title: BeginWrite()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous write operation.
type: docs
weight: 443
url: /cpp/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../../system/asynccallback/), [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>) method


Initiates an asynchronous write operation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The byte array to write data to. |
| offset | **int32_t** | The offset in bytes in the specified array. |
| count | **int32_t** | The number of bytes to write. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous write operation. |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous write operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
