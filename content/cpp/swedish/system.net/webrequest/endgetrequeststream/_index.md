---
title: EndGetRequestStream()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den angivna asynkrona operationen för att hämta en ström är klar.
type: docs
weight: 313
url: /sv/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metod

Väntar tills den angivna asynkrona operationen för att hämta en ström är klar.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron operation för att hämta en ström. |

### Returvärde

Strömmen för att skriva data till resursen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [WebRequest](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)