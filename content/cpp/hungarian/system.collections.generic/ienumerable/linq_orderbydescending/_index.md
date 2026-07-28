---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides C++ API Referenciája
description: A sorozat elemeit csökkenő sorrendben rendezi a keySelector által kiválasztott kulcsértékek szerint.
type: docs
weight: 222
url: /hu/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) metódus


Rendezi egy sorozat elemeit csökkenő sorrendben a keySelector által kiválasztott kulcsértékek szerint.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| keySelector | Egy függvény, amely egy elemből kulcsot nyer ki. |

### Visszatérési érték

Egy IOrderedEnumerable, amelynek elemei a kulcs csökkenő sorrendje szerint vannak rendezve

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) metódus




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Osztály [Func](../../../system/func/)
* Osztály [IEnumerable](../)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)