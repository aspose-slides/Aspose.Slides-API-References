---
title: EndGetResponse()
second_title: Aspose.Slides für C++ API Referenz
description: Wartet, bis die angegebene asynchrone Anforderung für die Ressource abgeschlossen ist.
type: docs
weight: 287
url: /de/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) Methode


Wartet, bis die angegebene asynchrone Anforderung für die Ressource abgeschlossen ist.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das eine asynchrone Anforderung für die Ressource darstellt. |

### Return Value

Die Webantwort.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [WebResponse](../../webresponse/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [WebRequest](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)