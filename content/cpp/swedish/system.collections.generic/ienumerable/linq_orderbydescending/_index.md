---
title: LINQ_OrderByDescending()
second_title: Aspose.Slides för C++ API-referens
description: Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som väljs av keySelector.
type: docs
weight: 222
url: /sv/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) metod


Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som väljs av keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| keySelector | En funktion för att extrahera en nyckel från ett element. |

### Returvärde

Ett IOrderedEnumerable vars element är sorterade i fallande ordning efter nyckeln

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) metod




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)