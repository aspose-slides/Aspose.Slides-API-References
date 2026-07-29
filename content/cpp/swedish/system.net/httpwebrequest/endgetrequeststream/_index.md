---
title: EndGetRequestStream()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den specificerade asynkrona operationen för att hämta en ström är klar.
type: docs
weight: 482
url: /sv/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metod


Väntar tills den angivna asynkrona operationen för att hämta en ström är klar.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/) objekt som representerar en asynkron operation för att hämta en ström. |

### Returvärde

Strömmen för att skriva data till resursen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../../system.io/stream/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [HttpWebRequest](../)
* Namnrymd [System::Net](../../)
* Library [Aspose.Slides](../../../)