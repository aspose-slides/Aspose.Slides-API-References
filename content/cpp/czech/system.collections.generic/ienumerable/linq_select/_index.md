---
title: LINQ_Select()
second_title: Aspose.Slides pro C++ API Reference
description: Transformuje prvky sekvence.
type: docs
weight: 248
url: /cs/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) metoda

Transformuje prvky sekvence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ResultType | Typ hodnoty vrácené **selector**. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Transformační funkce. |

### Návratová hodnota

[IEnumerable](../) obsahuje prvky vrácené funkcí **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) metoda

Transformuje každý prvek sekvence do nové podoby zahrnutím indexu prvku.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ResultType | Typ hodnoty vrácené **selector**. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Transformační funkce. |

### Návratová hodnota

[IEnumerable](../) obsahuje prvky vrácené funkcí **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) metoda

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) metoda

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IEnumerable](../)
* Třída [Func](../../../system/func/)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)