---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API Reference
description: Initiates an asynchronous request for the resource.
type: docs
weight: 170
url: /cpp/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) method


Initiates an asynchronous request for the resource.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)