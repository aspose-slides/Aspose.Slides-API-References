---
title: EndRead()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den angivna asynkrona läsoperationen slutförs.
type: docs
weight: 183
url: /sv/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) metod

Väntar tills den angivna asynkrona läsoperationen slutförs.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron läsoperation |

### Returvärde

Antalet byte som lästes under den läsoperation som representeras av **asyncResult**

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Stream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)