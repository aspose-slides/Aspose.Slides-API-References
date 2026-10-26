---
title: EndGetHostEntry()
second_title: Aspose.Slides C++ API referencia
description: Megvárja, amíg a megadott aszinkron művelet befejeződik, és egy új IPHostEntry-class példányt hoz létre.
type: docs
weight: 118
url: /hu/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry(System::SharedPtr\<IAsyncResult\>) metódus


Megvárja, amíg a megadott aszinkron művelet befejeződik és létrehoz egy új IPHostEntry-class példányt.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron műveletet képvisel. |

### Visszatérési érték

Egy újonnan létrehozott IPHostEntry-class példány.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IPHostEntry](../../iphostentry/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Dns](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)