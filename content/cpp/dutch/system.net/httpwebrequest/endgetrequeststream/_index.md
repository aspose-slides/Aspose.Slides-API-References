---
title: EndGetRequestStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot de opgegeven asynchrone bewerking om een stream op te halen is voltooid.
type: docs
weight: 482
url: /nl/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) method

Wacht tot de opgegeven asynchrone bewerking om een stream op te halen is voltooid.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Een [IAsyncResult](../../../system/iasyncresult/) object dat een asynchrone bewerking vertegenwoordigt om een stream op te halen. |

### Retourwaarde

De stream om data naar de bron te schrijven.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [HttpWebRequest](../)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)