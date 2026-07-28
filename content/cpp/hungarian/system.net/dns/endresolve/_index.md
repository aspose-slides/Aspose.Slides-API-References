---
title: EndResolve()
second_title: Aspose.Slides for C++ API Referencia
description: Megvárja, amíg a megadott aszinkron művelet befejeződik, amely egy új IPHostEntry-class példányt hoz létre.
type: docs
weight: 170
url: /hu/system.net/dns/endresolve/
---
## Dns::EndResolve(System::SharedPtr\<IAsyncResult\>) metódus


Megvárja, amíg a megadott aszinkron művelet befejeződik, amely egy új IPHostEntry-class példányt hoz létre.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron műveletet reprezentál. |

### Visszatérési érték

Egy újonnan létrehozott IPHostEntry-class példány.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPHostEntry](../../iphostentry/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Dns](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)