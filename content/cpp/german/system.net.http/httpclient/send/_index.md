---
title: Send()
second_title: Aspose.Slides für C++ API Referenz
description: Sendet die angegebene HTTP-Anfrage.
type: docs
weight: 118
url: /de/system.net.http/httpclient/send/
---
## HttpClient::Send(System::SharedPtr\<HttpRequestMessage\>, HttpCompletionOption) Methode

Sendet die angegebene HTTP-Anfrage.

```cpp
System::SharedPtr<HttpResponseMessage> System::Net::Http::HttpClient::Send(System::SharedPtr<HttpRequestMessage> request, HttpCompletionOption completionOption)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| request | [System::SharedPtr](../../../system/sharedptr/)\<[HttpRequestMessage](../../httprequestmessage/)\> | Die HTTP-Anfrage, die gesendet werden muss. |
| completionOption | [HttpCompletionOption](../../httpcompletionoption/) | Der Wert, der angibt, wann die Operation abgeschlossen werden soll. |

## Siehe auch

* Enum [HttpCompletionOption](../../httpcompletionoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HttpResponseMessage](../../httpresponsemessage/)
* Klasse [HttpRequestMessage](../../httprequestmessage/)
* Klasse [HttpClient](../)
* Namensraum [System::Net::Http](../../)
* Library [Aspose.Slides](../../../)