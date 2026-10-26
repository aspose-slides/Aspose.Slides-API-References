---
title: LINQ_Average()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Oblicza średnią ciągu wartości numerycznych.
type: docs
weight: 365
url: /pl/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Oblicza średnią ciągu wartości numerycznych.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### Wartość zwrotna

Średnia wartości w ciągu.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Oblicza średnią ciągu wartości uzyskanych przez wywołanie funkcji transformującej na każdym elemencie sekwencji wejściowej.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ResultType | Typ wartości zwracanej przez selector. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Funkcja transformująca stosowana do każdego elementu. |

### Wartość zwrotna

Średnia wartości projekcji.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Zobacz także

* Klasa [IEnumerable](../)
* Klasa [Func](../../../system/func/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)