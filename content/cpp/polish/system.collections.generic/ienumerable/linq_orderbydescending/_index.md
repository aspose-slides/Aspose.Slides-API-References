---
title: LINQ_OrderByDescending()
second_title: Referencja API Aspose.Slides dla C++
description: Sortuje elementy sekwencji w kolejności malejącej według wartości klucza wybranych przez keySelector.
type: docs
weight: 222
url: /pl/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) metoda

Sortuje elementy sekwencji w kolejności malejącej według wartości klucza wybranych przez keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| keySelector | Funkcja służąca do wyodrębnienia klucza z elementu. |

### Wartość zwracana

IOrderedEnumerable, którego elementy są posortowane w kolejności malejącej według klucza

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) metoda

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Klasa [Func](../../../system/func/)
* Klasa [IEnumerable](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)