---
title: EndGetRequestStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot de opgegeven asynchrone bewerking om een stream te verkrijgen is voltooid.
type: docs
weight: 157
url: /nl/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) methode

Wacht tot de opgegeven asynchrone bewerking om een stream te verkrijgen is voltooid.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone bewerking vertegenwoordigt om een stream te verkrijgen. |

### Retourwaarde

De stream voor het schrijven van gegevens naar de bron.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [FileWebRequest](../)
* Naamruimte [System::Net](../../)
* Library [Aspose.Slides](../../../)