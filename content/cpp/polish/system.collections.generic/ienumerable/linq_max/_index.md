---
title: LINQ_Max()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Wywołuje funkcję transformującą dla każdego elementu generycznej sekwencji i zwraca maksymalną otrzymaną wartość.
type: docs
weight: 352
url: /pl/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) metoda

Wywołuje funkcję transformującą dla każdego elementu generycznej sekwencji i zwraca maksymalną otrzymaną wartość.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ResultType | Typ wartości zwracanej przez selector. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Funkcja transformująca stosowana do każdego elementu. |

### Wartość zwracana

Maksymalna wartość w sekwencji.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) metoda

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Zobacz także

* Klasa [Func](../../../system/func/)
* Klasa [IEnumerable](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)