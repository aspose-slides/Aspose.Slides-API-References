---
title: LINQ_Min()
second_title: Aspose.Slides dla C++ - referencja API
description: Wywołuje funkcję transformującą na każdym elemencie generycznej sekwencji i zwraca minimalną otrzymaną wartość.
type: docs
weight: 339
url: /pl/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) metoda


Wywołuje funkcję transformującą na każdym elemencie generycznej sekwencji i zwraca minimalną otrzymaną wartość.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
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

Minimalna wartość w sekwencji.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) metoda




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Zobacz także

* Klasa [Func](../../../system/func/)
* Klasa [IEnumerable](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)