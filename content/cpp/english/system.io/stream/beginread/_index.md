---
title: BeginRead()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous read operation.
type: docs
weight: 118
url: /system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) method


Initiates an asynchronous read operation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A buffer to read to |
| offset | int | A 0-based offset in **buffer** indicating the position from which to start writing the read data |
| count | int | The number of bytes to read |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous read operation |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous read operation

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)