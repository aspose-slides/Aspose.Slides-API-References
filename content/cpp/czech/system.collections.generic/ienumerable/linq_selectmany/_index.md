---
title: LINQ_SelectMany()
second_title: Aspose.Slides pro C++ - reference API
description: Zpracuje každý prvek sekvence a sloučí výsledné sekvence do jedné sekvence.
type: docs
weight: 300
url: /cs/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method

Zpracuje každý prvek sekvence a sloučí výsledné sekvence do jedné sekvence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ResultType | Typ hodnoty vrácené **selector**. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Transformace funkce. |

### Návratová hodnota

[IEnumerable](../), který obsahuje výsledek volání projekční funkce typu jedna-na-mnoho na každý prvek vstupní sekvence.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)