---
title: AbstractEqual()
second_title: Aspose.Slides pro C++ – reference API
description: Porovnává dvě kolekce neznámého typu.
type: docs
weight: 14
url: /cs/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) metoda

Porovnává dvě kolekce neznámého typu.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementu kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Levá (LHS) kolekce. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Pravá (RHS) kolekce. |

### Návratová hodnota

true pokud se kolekce shodují (např. obě jsou null), nebo pokud se shodují velikosti a prvky, false jinak.

## Viz také

* Třída [ICollection](../../../system.collections.generic/icollection/)
* Struktura [TestCompare](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)