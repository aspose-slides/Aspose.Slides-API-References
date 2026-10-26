---
title: LINQ_OrderBy()
second_title: Aspose.Slides C++ API referencia
description: Rendezi egy sorozat elemeit növekvő sorrendbe a keySelector által kiválasztott kulcsértékek szerint.
type: docs
weight: 209
url: /hu/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) method

Rendezi egy sorozat elemeit növekvő sorrendbe a keySelector által kiválasztott key értékek szerint.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| keySelector | Egy függvény, amely egy Key-t von ki egy elemből. |

### Visszatérési érték

Egy IOrderedEnumerable, amelynek elemei egy kulcs szerint vannak rendezve

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) method

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Osztály [Func](../../../system/func/)
* Osztály [IEnumerable](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)