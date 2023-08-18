---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous operation to get a stream for writing data to the resource.
type: docs
weight: 300
url: /system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous operation to get a stream for writing data to the resource.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | A callback to be called when the operation completes. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | User-provided data used to uniquely identify each asynchronous operation. |

### Return Value

An [IAsyncResult](../../../system/iasyncresult/) object representing the initiated asynchronous operation.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)