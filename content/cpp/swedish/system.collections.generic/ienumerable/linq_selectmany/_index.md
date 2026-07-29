---
title: LINQ_SelectMany()
second_title: Aspose.Slides för C++ API-referens
description: Projektar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens.
type: docs
weight: 300
url: /sv/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Projektar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| ResultType | Typen av värdet som returneras av **selector**. |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | En transformationsfunktion. |

### Returvärde

Ett [IEnumerable](../) som innehåller resultatet av att anropa en en-till-många projektionfunktion på varje element i inmatningssekvensen.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IEnumerable](../)
* Klass [Func](../../../system/func/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)