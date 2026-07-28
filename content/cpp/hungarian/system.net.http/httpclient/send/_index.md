---
title: Send()
second_title: Aspose.Slides for C++ API referencia
description: Elküldi a megadott HTTP kérést.
type: docs
weight: 118
url: /hu/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) method

Elküldi a megadott HTTP kérést.

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | A HTTP kérés, amelyet el kell küldeni. |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | Az az érték, amely jelzi, mikor kell befejezni a műveletet. |

## Lásd még

* Enum [HttpCompletionOption](../../httpcompletionoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponseMessage](../../httpresponsemessage/)
* Class [HttpRequestMessage](../../httprequestmessage/)
* Class [HttpClient](../)
* Namespace [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)