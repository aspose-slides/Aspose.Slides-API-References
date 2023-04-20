---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous request for the resource.
type: docs
weight: 274
url: /cpp/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous request for the resource.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
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