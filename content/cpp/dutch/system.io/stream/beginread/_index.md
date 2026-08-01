---
title: BeginRead()
second_title: Aspose.Slides voor C++ API Referentie
description: Initieert een asynchrone leesbewerking.
type: docs
weight: 157
url: /nl/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) methode


Initieert een asynchrone leesbewerking.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Een buffer om in te lezen |
| offset | int | Een 0-gebaseerde offset in **buffer** die de positie aangeeft vanaf waar de gelezen gegevens moeten worden weggeschreven |
| count | int | Het aantal bytes om te lezen |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Door de gebruiker verstrekte gegevens die worden gebruikt om elke asynchrone leesbewerking uniek te identificeren |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/)-object dat de geïnitieerde asynchrone leesbewerking vertegenwoordigt

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [Stream](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)