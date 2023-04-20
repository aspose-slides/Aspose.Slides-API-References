---
title: HttpRequestMessage()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 131
url: /cpp/system.net.http/httprequestmessage/httprequestmessage/
---
## HttpRequestMessage::HttpRequestMessage() constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage()
```

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, System::SharedPtr\<Uri\>) constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, System::SharedPtr<Uri> requestUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | The HTTP method. |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The URI of the requested resource. |

## HttpRequestMessage::HttpRequestMessage(System::SharedPtr\<HttpMethod\>, String) constructor


Constructs a new instance.

```cpp
System::Net::Http::HttpRequestMessage::HttpRequestMessage(System::SharedPtr<HttpMethod> method, String requestUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| method | [System::SharedPtr](../../../system/sharedptr/)\<[HttpMethod](../../httpmethod/)\> | The HTTP method. |
| requestUri | [String](../../../system/string/) | The URI of the requested resource. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpRequestMessage](../)
* Class [HttpMethod](../../httpmethod/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)