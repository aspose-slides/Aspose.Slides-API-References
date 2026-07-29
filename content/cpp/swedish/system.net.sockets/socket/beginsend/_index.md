---
title: BeginSend()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron sändningsoperation.
type: docs
weight: 495
url: /sv/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) method


Initierar en asynkron sändningsoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | En buffert att läsa data från. |
| offset | **int32_t** | Förskjutningen i byte i den angivna arrayen. |
| size | **int32_t** | Antalet byte i den specificerade arrayen som startar från parametern 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Sändningsbeteendet. |
| callback | [AsyncCallback](../../../system/asynccallback/) | En återuppringningsfunktion som kommer att anropas när operationen slutförs. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererade data som används för att entydigt identifiera varje asynkron sändningsoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona sändningsoperationen.

## Se även

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)