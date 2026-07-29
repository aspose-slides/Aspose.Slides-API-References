---
title: EndGetResponse()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den angivna asynkrona förfrågan för resursen är färdig.
type: docs
weight: 508
url: /sv/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metod


Väntar tills den angivna asynkrona förfrågan för resursen är färdig.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron förfrågan för resursen. |

### Returvärde

Webbresponsen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [WebResponse](../../webresponse/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [HttpWebRequest](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)