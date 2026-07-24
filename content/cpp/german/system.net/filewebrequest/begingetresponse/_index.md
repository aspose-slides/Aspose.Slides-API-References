---
title: BeginGetResponse()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Anforderung für die Ressource.
type: docs
weight: 170
url: /de/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) Methode


Startet eine asynchrone Anforderung für die Ressource.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, das aufgerufen wird, wenn die Operation abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzerbereitgestellte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die gestartete asynchrone Operation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [FileWebRequest](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)