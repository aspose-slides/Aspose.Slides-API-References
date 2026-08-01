---
title: BeginSend()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone verzendoperatie.
type: docs
weight: 495
url: /nl/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) methode


Initieert een asynchrone verzendoperatie.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Een buffer om gegevens uit te lezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array, beginnend bij de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het verzendgedrag. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone verzendoperatie uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone verzendoperatie vertegenwoordigt.

## Zie ook

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [Socket](../)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)