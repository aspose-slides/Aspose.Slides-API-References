---
title: Send()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Odesílá zadaný HTTP požadavek.
type: docs
weight: 118
url: /cs/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) method

Odesílá zadaný HTTP požadavek.

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | HTTP požadavek, který musí být odeslán. |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | Hodnota, která určuje, kdy operaci dokončit. |

## Viz také

* Enum [HttpCompletionOption](../../httpcompletionoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [HttpResponseMessage](../../httpresponsemessage/)
* Třída [HttpRequestMessage](../../httprequestmessage/)
* Třída [HttpClient](../)
* Jmenný prostor [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)