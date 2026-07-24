---
title: EndGetResponse()
second_title: Aspose.Slides für C++ API Referenz
description: Wartet, bis die angegebene asynchrone Anforderung für die Ressource abgeschlossen ist.
type: docs
weight: 183
url: /de/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) Methode

Wartet, bis die angegebene asynchrone Anforderung für die Ressource abgeschlossen ist.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das eine asynchrone Anforderung für die Ressource darstellt. |

### Rückgabewert

Die Webantwort.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [WebResponse](../../webresponse/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [FileWebRequest](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)