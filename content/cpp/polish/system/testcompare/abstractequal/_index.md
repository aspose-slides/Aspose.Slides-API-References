---
title: AbstractEqual()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Porównuje dwie kolekcje nieznanego typu.
type: docs
weight: 14
url: /pl/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) metoda

Porównuje dwie kolekcje nieznanego typu.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementu kolekcji. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Kolekcja po lewej stronie. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Kolekcja po prawej stronie. |

### Wartość zwracana

true jeśli kolekcje są zgodne (np. obie są null), lub jeśli rozmiary są zgodne i elementy są zgodne, false w przeciwnym razie.

## Zobacz także

* Klasa [ICollection](../../../system.collections.generic/icollection/)
* Struktura [TestCompare](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)