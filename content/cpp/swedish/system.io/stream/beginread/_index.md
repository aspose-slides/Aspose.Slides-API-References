---
title: BeginRead()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron läsoperation.
type: docs
weight: 157
url: /sv/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metod


Initierar en asynkron läsoperation.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En buffer att läsa till |
| offset | int | En nollbaserad förskjutning i **buffer** som anger positionen varifrån den lästa datan ska skrivas |
| count | int | Antalet byte att läsa |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska kallas när operationen är klar |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Användarlevererad data som används för att unikt identifiera varje asynkron läsoperation |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona läsoperationen

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [Stream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)