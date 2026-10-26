---
title: LINQ_Select()
second_title: Aspose.Slides för C++ API-referens
description: Omvandlar element i en sekvens.
type: docs
weight: 248
url: /sv/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) metod


Omvandlar element i en sekvens.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av **selector**. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | En transformfunktion. |

### Returvärde

En [IEnumerable](../) som innehåller element som returnerats av **selector**-funktionen.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) metod


Omvandlar varje element i en sekvens till en ny form genom att inkludera elementets index.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av **selector**. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | En transformfunktion. |

### Returvärde

En [IEnumerable](../) som innehåller element som returnerats av **selector**-funktionen.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) metod




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) metod




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IEnumerable](../)
* Klass [Func](../../../system/func/)
* Namnrymd [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)