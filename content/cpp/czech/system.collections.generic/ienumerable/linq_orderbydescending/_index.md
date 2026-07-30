---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Seřadí prvky sekvence sestupně podle hodnot klíče vybraných pomocí keySelector.
type: docs
weight: 222
url: /cs/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) metoda

Seřadí prvky posloupnosti sestupně podle hodnot klíče vybraných pomocí keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| keySelector | Funkce pro získání klíče z elementu. |

### Návratová hodnota

IOrderedEnumerable, jehož prvky jsou seřazeny sestupně podle klíče

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) metoda

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Třída [Func](../../../system/func/)
* Třída [IEnumerable](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)