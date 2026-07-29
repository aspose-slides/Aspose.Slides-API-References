---
title: EndReceive()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den specificerade asynkrona mottagningsoperationen slutförs.
type: docs
weight: 534
url: /sv/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) metod


Väntar tills den specificerade asynkrona mottagningsoperationen slutförs.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron mottagningsoperation. |

### Returvärde

Antalet byte som tas emot.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) metod


Väntar tills den specificerade asynkrona mottagningsoperationen slutförs.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron mottagningsoperation. |
| errorCode | [SocketError](../../socketerror/)\& | Utdata-parametern där felkoden kommer att tilldelas när mottagningsoperationen misslyckas. |

### Returvärde

Antalet mottagna byte.

## Se även

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Socket](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)