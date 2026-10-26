---
title: EndGetRequestStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Operation zum Abrufen eines Streams abgeschlossen ist.
type: docs
weight: 482
url: /de/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) Methode

Wartet, bis die angegebene asynchrone Operation zum Abrufen eines Streams abgeschlossen ist.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das eine asynchrone Operation zum Abrufen eines Streams darstellt. |

### Rückgabewert

Der Stream zum Schreiben von Daten in die Ressource.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [HttpWebRequest](../)
* Namensraum [System::Net](../../)
* Library [Aspose.Slides](../../../)