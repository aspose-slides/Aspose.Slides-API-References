---
title: LINQ_OrderBy()
second_title: Aspose.Slides för C++ API-referens
description: Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som väljs av keySelector.
type: docs
weight: 209
url: /sv/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) metod

Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som väljs av keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| keySelector | En funktion för att extrahera en nyckel från ett element. |

### Returvärde

En IOrderedEnumerable vars element är sorterade enligt en nyckel

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) metod




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Klass [Func](../../../system/func/)
* Klass [IEnumerable](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)