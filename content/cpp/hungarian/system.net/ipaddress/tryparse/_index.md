---
title: TryParse()
second_title: Aspose.Slides for C++ API referencia
description: Megpróbálja a megadott karakterláncot átalakítani az IPAddress osztály egy példányává.
type: docs
weight: 222
url: /hu/system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) metódus

Megkísérli egy átadott karakterlánc átalakítását a [IPAddress](../) osztály egy példányává.

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | A feldolgozandó karakterlánc. |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | Az a példány, amelyhez a feldolgozott objektum lesz hozzárendelve. |

### Visszatérési érték

True, ha a feldolgozás sikeresen megtörtént, különben false.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [IPAddress](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)