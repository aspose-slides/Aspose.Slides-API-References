---
title: BeginWrite()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous write operation.
type: docs
weight: 131
url: /cpp/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) method


Initiates an asynchronous write operation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A buffer containing data to be written |
| offset | int | A 0-based offset in **buffer** indicating the position from which the data to write begins |
| count | int | The number of bytes to write |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous write operation |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous write operation

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)