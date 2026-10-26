---
title: BeginGetRequestStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Initiiert eine asynchrone Operation, um einen Stream zum Schreiben von Daten in die Ressource zu erhalten.
type: docs
weight: 144
url: /de/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Operation, um einen Stream zum Schreiben von Daten in die Ressource zu erhalten.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein callback, der aufgerufen wird, wenn die Operation abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzerbereitgestellte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die initiierte asynchrone Operation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [FileWebRequest](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)