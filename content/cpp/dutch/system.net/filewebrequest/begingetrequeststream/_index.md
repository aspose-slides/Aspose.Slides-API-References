---
title: BeginGetRequestStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone bewerking om een stroom te verkrijgen voor het schrijven van gegevens naar de bron.
type: docs
weight: 144
url: /nl/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) methode

Initieert een asynchrone bewerking om een stroom te verkrijgen voor het schrijven van gegevens naar de bron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking voltooid is. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone bewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone bewerking vertegenwoordigt.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)