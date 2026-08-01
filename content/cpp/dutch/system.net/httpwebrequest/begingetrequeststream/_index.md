---
title: BeginGetRequestStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Start een asynchrone bewerking om een stroom te verkrijgen voor het schrijven van gegevens naar de bron.
type: docs
weight: 469
url: /nl/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) methode

Start een asynchrone bewerking om een stroom te verkrijgen voor het schrijven van gegevens naar de bron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking voltooid is. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Gebruiker-geleverde data die wordt gebruikt om elke asynchrone bewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de gestartte asynchrone bewerking vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [HttpWebRequest](../)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)