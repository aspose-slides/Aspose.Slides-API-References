---
title: BeginGetResponse()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone aanvraag voor de bron.
type: docs
weight: 495
url: /nl/system.net/httpwebrequest/begingetresponse/
---
## HttpWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) methode

Initieert een asynchrone aanvraag voor de bron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone bewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone bewerking voorstelt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [HttpWebRequest](../)
* Naamruimte [System::Net](../../)
* Library [Aspose.Slides](../../../)