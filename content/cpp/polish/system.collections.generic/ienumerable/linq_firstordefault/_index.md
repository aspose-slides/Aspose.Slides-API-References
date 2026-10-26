---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca pierwszy element ciągu lub wartość domyślną, jeśli ciąg jest pusty.
type: docs
weight: 66
url: /pl/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() metoda

Zwraca pierwszy element ciągu lub wartość domyślną, jeśli ciąg jest pusty.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```

### Wartość zwracana

Pierwszy element w ciągu lub wartość utworzoną domyślnie, jeśli ciąg jest pusty.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) metoda

Zwraca pierwszy element ciągu, który spełnia warunek, lub wartość domyślną, jeśli taki element nie zostanie znaleziony.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Funkcja testująca każdy element pod kątem warunku. |

### Wartość zwracana

default(T) jeśli źródło jest puste lub żaden element nie przechodzi testu określonego przez predicate; w przeciwnym razie pierwszy element w źródle, który przechodzi test określony przez predicate.

## Zobacz także

* Klasa [IEnumerable](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)