---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API Reference
description: Waits until the specified asynchronous request for the resource completes.
type: docs
weight: 183
url: /system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous request for the resource completes.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous request for the resource. |

### Return Value

The web response.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebResponse](../../webresponse/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)