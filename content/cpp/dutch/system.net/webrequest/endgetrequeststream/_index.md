---
title: EndGetRequestStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht totdat de opgegeven asynchrone bewerking om een stream te verkrijgen voltooid is.
type: docs
weight: 313
url: /nl/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) methode

Wacht totdat de opgegeven asynchrone bewerking om een stream te verkrijgen voltooid is.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone bewerking om een stream te verkrijgen voorstelt. |

### Retourwaarde

De stream voor het schrijven van gegevens naar de resource.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [WebRequest](../)
* Namespace [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)