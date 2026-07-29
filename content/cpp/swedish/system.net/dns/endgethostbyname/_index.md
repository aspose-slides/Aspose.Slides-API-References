---
title: EndGetHostByName()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-class-instans är klar.
type: docs
weight: 66
url: /sv/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) metod


Väntar tills den angivna asynkrona operationen för att skapa en ny IPHostEntry-klassinstans är klar.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/)-objekt som representerar en asynkron operation. |

### Returvärde

En ny skapad IPHostEntry-klassinstans.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPHostEntry](../../iphostentry/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Dns](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)