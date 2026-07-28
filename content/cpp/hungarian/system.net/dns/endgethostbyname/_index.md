---
title: EndGetHostByName()
second_title: Aspose.Slides C++ API hivatkozás
description: Vár, amíg a megadott aszinkron művelet, amely egy új IPHostEntry-osztály példányt hoz létre, befejeződik.
type: docs
weight: 66
url: /hu/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) metódus

Vár, amíg a megadott aszinkron művelet, amely egy új IPHostEntry-osztály példányt hoz létre, befejeződik.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely egy aszinkron műveletet képvisel. |

### Visszatérési érték

Egy újonnan létrehozott IPHostEntry-osztály példány.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IPHostEntry](../../iphostentry/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [Dns](../)
* Névtere [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)