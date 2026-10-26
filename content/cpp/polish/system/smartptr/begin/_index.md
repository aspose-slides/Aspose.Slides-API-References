---
title: begin()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Akcesor dla metody begin() kolekcji bazowej. Kompiluje się tylko wtedy, gdy SmartPtr_ jest typem specjalizacji z metodą begin().
type: docs
weight: 378
url: /pl/system/smartptr/begin/
---
## SmartPtr::begin() metoda


Akcesor dla metody [begin()](./) kolekcji bazowej. Kompiluje się tylko wtedy, gdy SmartPtr_ jest typem specjalizacji z metodą [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### Wartość zwracana

iterator do początku kolekcji

## SmartPtr::begin() const metoda


Akcesor dla metody [begin()](./) kolekcji bazowej. Kompiluje się tylko wtedy, gdy SmartPtr_ jest typem specjalizacji z metodą [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### Wartość zwracana

iterator do początku kolekcji

## Zobacz także

* Klasa [SmartPtr](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)