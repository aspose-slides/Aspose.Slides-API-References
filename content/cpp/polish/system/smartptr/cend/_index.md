---
title: cend()
second_title: Aspose.Slides – dokumentacja API dla C++
description: Akcesor dla metody cend() podlegającej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą cend().
type: docs
weight: 417
url: /pl/system/smartptr/cend/
---
## SmartPtr::cend() const metoda

Akcesor dla [cend()](./) metody podlegającej kolekcji. Kompiluje się tylko, jeśli SmartPtr_ jest typem specjalizacji z metodą [cend()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### Wartość zwracana

iterator do końca kolekcji

## Zobacz także

* Klasa [SmartPtr](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)