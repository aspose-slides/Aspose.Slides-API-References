---
title: end()
second_title: Referencja API Aspose.Slides dla C++
description: Akcesor dla metody end() podlegającej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą end().
type: docs
weight: 391
url: /pl/system/smartptr/end/
---
## SmartPtr::end() metoda


Akcesor dla [end()](./) metoda podlegającej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```


### Wartość zwracana

iterator do końca kolekcji

## SmartPtr::end() const metoda


Akcesor dla [end()](./) metoda podlegającej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```


### Wartość zwracana

iterator do końca kolekcji

## See Also

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)