---
title: LINQ_ThenBy()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wykonuje dodatkowe sortowanie elementów w sekwencji w kolejności rosnącej według klucza.
type: docs
weight: 27
url: /pl/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) metoda

Wykonuje dodatkowe sortowanie elementów w sekwencji w kolejności rosnącej według klucza.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Key | Typ klucza zwracanego przez keySelector. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Funkcja służąca do wyodrębnienia klucza z każdego elementu. |

### Wartość zwracana

[System::Linq::IOrderedEnumerable](../) którego elementy są sortowane według klucza.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) metoda




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IOrderedEnumerable](../)
* Klasa [Func](../../../system/func/)
* przestrzeń nazw [System::Linq](../../)
* Biblioteka [Aspose.Slides](../../../)