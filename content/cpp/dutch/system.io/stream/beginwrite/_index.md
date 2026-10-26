---
title: BeginWrite()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone schrijfoperatie.
type: docs
weight: 170
url: /nl/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) methode

Initieert een asynchrone schrijfoperatie.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Een buffer die gegevens bevat die geschreven moeten worden |
| offset | int | Een 0-gebaseerde offset in **buffer** die de positie aangeeft vanaf waar de te schrijven gegevens beginnen |
| count | int | Het aantal bytes om te schrijven |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone schrijfoperatie uniek te identificeren |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone schrijfoperatie vertegenwoordigt

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [Stream](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)