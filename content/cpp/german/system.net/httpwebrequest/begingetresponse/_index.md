---
title: BeginGetResponse()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Anforderung für die Ressource.
type: docs
weight: 495
url: /de/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) method


Startet eine asynchrone Anforderung für die Ressource.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, das aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzergesteuerte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die gestartete asynchrone Operation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [HttpWebRequest](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)