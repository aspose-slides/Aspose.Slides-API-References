---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API Reference
description: Waits until the specified asynchronous operation to get a stream completes.
type: docs
weight: 482
url: /cpp/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) method


Waits until the specified asynchronous operation to get a stream completes.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | An [IAsyncResult](../../../system/iasyncresult/) object that represents an asynchronous operation to get a stream. |

### Return Value

The stream for writing data to the resource.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)