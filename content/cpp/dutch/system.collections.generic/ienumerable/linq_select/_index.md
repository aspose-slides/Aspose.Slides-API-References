---
title: LINQ_Select()
second_title: Aspose.Slides voor C++ API-referentie
description: Transformeert elementen van een reeks.
type: docs
weight: 248
url: /nl/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) methode


Transformeert elementen van een reeks.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | A transform function. |

### Retourwaarde

Een [IEnumerable](../) die elementen bevat die door de **selector**-functie worden geretourneerd.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) methode


Transformeert elk element van een reeks naar een nieuwe vorm door de index van het element op te nemen.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | A transform function. |

### Retourwaarde

Een [IEnumerable](../) die elementen bevat die door de **selector**-functie worden geretourneerd.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) methode




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) methode




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IEnumerable](../)
* Klasse [Func](../../../system/func/)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)