---
title: BeginWrite()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en asynkron skrivoperation.
type: docs
weight: 443
url: /sv/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod

Initierar en asynkron skrivoperation.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytearrayen att skriva data till. |
| offset | **int32_t** | Offseten i byte i den angivna arrayen. |
| count | **int32_t** | Antalet byte att skriva. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | En återuppringning som ska anropas när operationen är klar. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Användarlevererad data som används för att unikt identifiera varje asynkron skrivoperation. |

### Returvärde

Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar den initierade asynkrona skrivoperationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Object](../../../system/object/)
* Klass [SslStream](../)
* Namnrymd [System::Net::Security](../../)
* Bibliotek [Aspose.Slides](../../../)