---
title: BeginGetRequestStream()
second_title: Aspose.Slides für C++ API Referenz
description: Startet eine asynchrone Operation, um einen Stream zum Schreiben von Daten in die Ressource zu erhalten.
type: docs
weight: 300
url: /de/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) Methode


Startet eine asynchrone Operation, um einen Stream zum Schreiben von Daten in die Ressource zu erhalten.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, der aufgerufen wird, wenn die Operation abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die gestartete asynchrone Operation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [WebRequest](../)
* Namensraum [System::Net](../../)
* Library [Aspose.Slides](../../../)