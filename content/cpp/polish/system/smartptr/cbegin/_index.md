---
title: cbegin()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Akcesor dla metody cbegin() podkładanej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą cbegin().
type: docs
weight: 404
url: /pl/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const metoda

Akcesor dla metody [cbegin()](./) podkładanej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Wartość zwracana

iterator do początku kolekcji

## Zobacz także

* Klasa [SmartPtr](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)