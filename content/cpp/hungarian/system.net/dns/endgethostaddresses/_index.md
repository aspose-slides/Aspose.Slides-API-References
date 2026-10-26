---
title: EndGetHostAddresses()
second_title: Aspose.Slides C++ API referencia
description: Várja meg, amíg a megadott aszinkron művelet, amely egy új IPHostEntry-class példányt hoz létre, befejeződik.
type: docs
weight: 144
url: /hu/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) metódus

Várja meg, amíg a megadott aszinkron művelet, amely egy új IPHostEntry-class példányt hoz létre, befejeződik.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron műveletet képvisel. |

### Visszatérési érték

Egy újonnan létrehozott IPHostEntry-class példány.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPAddress](../../ipaddress/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Dns](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)