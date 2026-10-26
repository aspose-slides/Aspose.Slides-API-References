---
title: AbstractEqual()
second_title: Aspose.Slides a C++ API Referenciája
description: Két ismeretlen típusú gyűjteményt hasonlít össze.
type: docs
weight: 14
url: /hu/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) metódus


Két ismeretlen típusú gyűjteményt hasonlít össze.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | A gyűjtemény elemtípusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Bal oldali gyűjtemény. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Jobb oldali gyűjtemény. |

### Visszatérési érték

true, ha a gyűjtemények egyeznek (pl. mindkettő null), vagy ha a méretek egyeznek és az elemek egyeznek, false egyébként.

## Lásd még

* Osztály [ICollection](../../../system.collections.generic/icollection/)
* Struktúra [TestCompare](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)