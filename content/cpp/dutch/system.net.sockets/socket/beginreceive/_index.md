---
title: BeginReceive()
second_title: Aspose.Slides voor C++ API-referentie
description: Initieert een asynchrone schrijfoperatie.
type: docs
weight: 521
url: /nl/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) methode


Initieert een asynchrone schrijfoperatie.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Een buffer waarin de ontvangen gegevens worden toegewezen. |
| offset | **int32_t** | De offset in bytes in de opgegeven array. |
| size | **int32_t** | Het aantal bytes in de opgegeven array beginnend vanaf de parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Het ontvangstgedrag. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Een callback die wordt aangeroepen wanneer de bewerking is voltooid. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Door de gebruiker geleverde gegevens die worden gebruikt om elke asynchrone ontvangstbewerking uniek te identificeren. |

### Retourwaarde

Een [IAsyncResult](../../../system/iasyncresult/) object dat de geïnitieerde asynchrone ontvangstbewerking vertegenwoordigt.

## Zie ook

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)