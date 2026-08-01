---
title: BeginGetRequestStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone bewerking om een stream te verkrijgen voor het schrijven van gegevens naar de bron.
type: docs
weight: 300
url: /nl/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) methode

Initieert een asynchrone bewerking om een stream te verkrijgen voor het schrijven van gegevens naar de bron.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking voltooid is. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone bewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone bewerking voorstelt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)