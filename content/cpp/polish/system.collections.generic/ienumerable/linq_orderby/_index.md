---
title: LINQ_OrderBy()
second_title: Aspose.Slides dla C++ dokumentacja API
description: Sortuje elementy sekwencji w kolejności rosnącej zgodnie z wartościami klucza wybranymi przez keySelector.
type: docs
weight: 209
url: /pl/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) metoda


Sortuje elementy sekwencji w kolejności rosnącej zgodnie z wartościami klucza wybranymi przez keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| keySelector | Funkcja służąca do wyodrębnienia klucza z elementu. |

### Wartość zwracana

IOrderedEnumerable, którego elementy są posortowane zgodnie z kluczem

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) metoda




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Klasa [Func](../../../system/func/)
* Klasa [IEnumerable](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)