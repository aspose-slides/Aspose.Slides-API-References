---
title: BeginWrite()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron skrivoperation.
type: docs
weight: 170
url: /sv/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metod

Initierar en asynkron skrivoperation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En buffert som innehåller data som ska skrivas |
| offset | int | En 0-baserad offset i **buffer** som indikerar positionen där datan som ska skrivas börjar |
| count | int | Antalet byte som ska skrivas |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | En återuppringningsfunktion som ska anropas när operationen är klar |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Användargenererad data som används för att unikt identifiera varje asynkron skrivoperation |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona skrivoperationen

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [Stream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)