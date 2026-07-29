---
title: EndGetResponse()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den specificerade asynkrona förfrågan om resursen slutförs.
type: docs
weight: 183
url: /sv/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) method


Väntar tills den specificerade asynkrona förfrågan om resursen slutförs.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron förfrågan om resursen. |

### Returvärde

Webbresponsen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [WebResponse](../../webresponse/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [FileWebRequest](../)
* Namnrymd [System::Net](../../)
* Library [Aspose.Slides](../../../)