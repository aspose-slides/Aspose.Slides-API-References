---
title: LINQ_Select()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przekształca elementy sekwencji.
type: docs
weight: 248
url: /pl/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) metoda

Przekształca elementy sekwencji.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ResultType | Typ wartości zwracanej przez funkcję **selector**. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Funkcja przekształcająca. |

### Wartość zwracana

Obiekt [IEnumerable](../) zawierający elementy zwrócone przez funkcję **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) metoda

Przekształca każdy element sekwencji w nową formę, uwzględniając indeks elementu.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ResultType | Typ wartości zwracanej przez funkcję **selector**. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Funkcja przekształcająca. |

### Wartość zwracana

Obiekt [IEnumerable](../) zawierający elementy zwrócone przez funkcję **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) metoda




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) metoda




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)