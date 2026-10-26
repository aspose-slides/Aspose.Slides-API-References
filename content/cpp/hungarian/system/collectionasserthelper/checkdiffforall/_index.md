---
title: CheckDiffForAll()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy a gyűjtemény összes eleme megfelel-e a feltételnek.
type: docs
weight: 14
url: /hu/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metódus

Ellenőrzi, hogy a gyűjtemény összes eleme megfelel-e a feltételnek.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Ellenőrzendő feltétel. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Ellenőrzendő értékek. |

### Visszatérési érték

False, ha a ellenőrzés bármely elemnél sikertelen, true, ha mindegyik átmegy.

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [ICollection](../../../system.collections.generic/icollection/)
* Struktúra [CollectionAssertHelper](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)