---
title: LINQ_SelectMany()
second_title: Aspose.Slides voor C++ API-referentie
description: Projecteert elk element van een reeks en combineert de resulterende reeksen tot één reeks.
type: docs
weight: 300
url: /nl/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) methode

Projecteert elk element van een reeks en combineert de resulterende reeksen tot één reeks.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ResultType | Het type van de waarde die wordt geretourneerd door de **selector**. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Een transformatiefunctie. |

### Retourwaarde

Een [IEnumerable](../) die het resultaat bevat van het aanroepen van een één-op-veel projectiefunctie op elk element van de invoerreeks.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) methode

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)