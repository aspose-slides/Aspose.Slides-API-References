---
title: EndGetRequestStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Operation zum Abrufen eines Streams abgeschlossen ist.
type: docs
weight: 157
url: /de/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) Methode

Wartet, bis die angegebene asynchrone Operation zum Abrufen eines Streams abgeschlossen ist.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das eine asynchrone Operation zum Abrufen eines Streams darstellt. |

### Rückgabewert

Der Stream zum Schreiben von Daten in die Ressource.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [FileWebRequest](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)