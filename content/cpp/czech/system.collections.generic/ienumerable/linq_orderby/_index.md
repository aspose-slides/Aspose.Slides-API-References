---
title: LINQ_OrderBy()
second_title: Aspose.Slides pro C++ - reference API
description: Seřadí prvky sekvence vzestupně podle hodnot klíčů vybraných pomocí keySelectoru.
type: docs
weight: 209
url: /cs/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) metoda

Seřadí prvky sekvence vzestupně podle hodnot klíčů vybraných pomocí keySelectoru.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| keySelector | Funkce pro získání klíče z prvku. |

### Návratová hodnota

IOrderedEnumerable, jehož prvky jsou seřazeny podle klíče

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) metoda

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* třída [Func](../../../system/func/)
* třída [IEnumerable](../)
* jmenný prostor [System::Collections::Generic](../../)
* knihovna [Aspose.Slides](../../../)