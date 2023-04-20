---
title: Send()
second_title: Aspose.Slides for C++ API Reference
description: Sends the specified HTTP request.
type: docs
weight: 118
url: /cpp/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) method


Sends the specified HTTP request.

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | The HTTP request that must be sent. |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | The value that indicates when to complete the operation. |

## See Also

* Enum [HttpCompletionOption](../../httpcompletionoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponseMessage](../../httpresponsemessage/)
* Class [HttpRequestMessage](../../httprequestmessage/)
* Class [HttpClient](../)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)