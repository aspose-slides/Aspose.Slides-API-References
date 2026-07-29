---
title: EndRead()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den angivna asynkrona läsoperationen slutförs.
type: docs
weight: 261
url: /sv/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) metod


Väntar tills den angivna asynkrona läsoperationen slutförs.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/) objekt som representerar en asynkron läsoperation |

### Returvärde

Antalet byte som lästs under läsoperationen som representeras av **asyncResult**

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [NetworkStream](../)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)