---
title: LINQ_ThenBy()
second_title: Aspose.Slides C++ API referenciája
description: Egy sorozat elemeinek további rendezését végzi növekvő sorrendben egy kulcs alapján.
type: docs
weight: 27
url: /hu/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method

Egy sorozat elemeinek további rendezését végzi növekvő sorrendben egy kulcs alapján.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Key | A keySelector által visszaadott kulcs típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Egy függvény, amely kulcsot nyer ki minden elemből. |

### Visszatérési érték

[System::Linq::IOrderedEnumerable](../) amelynek elemei egy kulcs szerint vannak rendezve.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IOrderedEnumerable](../)
* Osztály [Func](../../../system/func/)
* Névtér [System::Linq](../../)
* Könyvtár [Aspose.Slides](../../../)