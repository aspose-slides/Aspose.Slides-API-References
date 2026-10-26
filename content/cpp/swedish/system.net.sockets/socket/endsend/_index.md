---
title: EndSend()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den angivna asynkrona sändningsoperationen slutförs.
type: docs
weight: 508
url: /sv/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) metod


Väntar tills den angivna asynkrona sändningsoperationen slutförs.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron sändningsoperation. |

### Returvärde

Antalet skickade byte.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) metod


Väntar tills den angivna asynkrona sändningsoperationen slutförs.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron sändningsoperation. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden kommer att tilldelas när sändningsoperationen misslyckas. |

### Returvärde

Antalet skickade byte.

## Se även

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Socket](../)
* Namnområde [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)