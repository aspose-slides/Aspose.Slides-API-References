---
title: EndGetHostEntry()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den specificerade asynkrona operationen för att skapa en ny IPHostEntry-class instans är klar.
type: docs
weight: 118
url: /sv/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry(System::SharedPtr\<IAsyncResult\>) metod

Väntar tills den specificerade asynkrona operationen som skapar en ny IPHostEntry-klassinstans är klar.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
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
* Library [Aspose.Slides](../../../)