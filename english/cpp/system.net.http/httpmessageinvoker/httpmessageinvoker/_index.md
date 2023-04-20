---
title: HttpMessageInvoker()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 1
url: /cpp/system.net.http/httpmessageinvoker/httpmessageinvoker/
---
## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>) constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | The HTTP handler used for sending requests. |

## HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr\<HttpMessageHandler\>, bool) constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpMessageInvoker::HttpMessageInvoker(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | The HTTP handler used for sending requests. |
| disposeHandler | **bool** | The value that indicates if the handler must be disposed when this instance is disposed. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpMessageHandler](../../httpmessagehandler/)
* Class [HttpMessageInvoker](../)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)