---
title: BeginWrite()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron skrivoperation.
type: docs
weight: 274
url: /sv/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron skrivoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En buffer som innehåller data som ska skrivas. |
| offset | **int32_t** | Offseten i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte att skriva. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ett återanrop som ska anropas när operationen slutförs. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererad data som används för att unikt identifiera varje asynkron skrivoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona skrivoperationen.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [NetworkStream](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)