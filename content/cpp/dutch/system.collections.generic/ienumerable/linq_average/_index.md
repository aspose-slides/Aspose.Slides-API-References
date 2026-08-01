---
title: LINQ_Average()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent het gemiddelde van een reeks numerieke waarden.
type: docs
weight: 365
url: /nl/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Berekent het gemiddelde van een reeks numerieke waarden.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### Retourwaarde

Het gemiddelde van de waarden in de reeks.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Berekent het gemiddelde van een reeks waarden die worden verkregen door een transformatie-functie aan te roepen op elk element van de invoersequentie.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ResultType | Het type van de waarde die door selector wordt geretourneerd. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Een transformatie-functie die op elk element wordt toegepast. |

### Retourwaarde

Het gemiddelde van de geprojecteerde waarden.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Zie ook

* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)