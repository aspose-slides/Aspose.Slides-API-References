---
title: HttpClient()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 92
url: /system.net.http/httpclient/httpclient/
---
## HttpClient::HttpClient() constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpClient::HttpClient()
```

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>) constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | The HTTP handler used for sending requests. |

## HttpClient::HttpClient(System::SharedPtr\<HttpMessageHandler\>, bool) constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpClient::HttpClient(System::SharedPtr<HttpMessageHandler> handler, bool disposeHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| handler | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMessageHandler](../../httpmessagehandler/)\> | The HTTP handler used for sending requests. |
| disposeHandler | **bool** | The value that indicates if the handler must be disposed when this instance is disposed. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpClient](../)
* Class [HttpMessageHandler](../../httpmessagehandler/)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)