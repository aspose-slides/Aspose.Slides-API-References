---
title: EndGetRequestStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis der angegebene asynchrone Vorgang zum Abrufen eines Streams abgeschlossen ist.
type: docs
weight: 313
url: /de/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) Methode

Wartet, bis der angegebene asynchrone Vorgang zum Abrufen eines Streams abgeschlossen ist.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das einen asynchronen Vorgang zum Abrufen eines Streams darstellt. |

### Rückgabewert

Der Stream zum Schreiben von Daten in die Ressource.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [WebRequest](../)
* Namensraum [System::Net](../../)
* Library [Aspose.Slides](../../../)