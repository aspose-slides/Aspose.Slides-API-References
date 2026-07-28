---
title: LINQ_SelectMany()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Projektuje każdy element sekwencji i łączy uzyskane sekwencje w jedną sekwencję.
type: docs
weight: 300
url: /pl/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) metoda

Projektuje każdy element sekwencji i łączy uzyskane sekwencje w jedną sekwencję.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ResultType | Typ wartości zwracanej przez **selector**. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Funkcja transformująca. |

### Wartość zwracana

Obiekt [IEnumerable](../) zawierający wynik wywołania funkcji projekcji jeden-do-wielu na każdym elemencie sekwencji wejściowej.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) metoda

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IEnumerable](../)
* Klasa [Func](../../../system/func/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)