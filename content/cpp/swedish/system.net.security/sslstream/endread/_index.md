---
title: EndRead()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den angivna asynkrona läsoperationen är klar.
type: docs
weight: 430
url: /sv/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) metod

Väntar tills den angivna asynkrona läsoperationen är klar.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron läsoperation |

### Returvärde

Antalet byte som lästes under läsoperationen som representeras av **asyncResult**

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [SslStream](../)
* Namnrymd [System::Net::Security](../../)
* Bibliotek [Aspose.Slides](../../../)