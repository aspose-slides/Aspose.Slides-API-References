---
title: EndGetHostAddresses()
second_title: Aspose.Slides för C++ API-referens
description: Väntar tills den specificerade asynkrona operationen för att skapa en ny IPHostEntry-klassinstans slutförs.
type: docs
weight: 144
url: /sv/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) metod

Väntar tills den specificerade asynkrona operationen för att skapa en ny IPHostEntry-klassinstans slutförs.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ett [IAsyncResult](../../../system/iasyncresult/) objekt som representerar en asynkron operation. |

### Returvärde

En ny skapad IPHostEntry-klassinstans.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPAddress](../../ipaddress/)
* Klass [IAsyncResult](../../../system/iasyncresult/)
* Klass [Dns](../)
* Namnrymd [System::Net](../../)
* Library [Aspose.Slides](../../../)