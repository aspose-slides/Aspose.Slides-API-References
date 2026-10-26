---
title: BeginReceive()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron skrivoperation.
type: docs
weight: 521
url: /sv/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metod


Initierar en asynkron skrivoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En buffert där de mottagna data kommer att tilldelas. |
| offset | **int32_t** | Förskjutningen i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte i den angivna arrayen som startar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Mottagningsbeteendet. |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som kommer att anropas när operationen är klar. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att unikt identifiera varje asynkron mottagningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona mottagningsoperationen.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [Socket](../)
* Namnrymd [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)