---
title: LINQ_Min()
second_title: Aspose.Slides voor C++ API Referentie
description: Roept een transformatiefunctie aan voor elk element van een generieke reeks en retourneert de minimaal resulterende waarde.
type: docs
weight: 339
url: /nl/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) methode

Roept een transformatiefunctie aan voor elk element van een generieke reeks en retourneert de minimaal resulterende waarde.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ResultType | Het type van de waarde die door selector wordt geretourneerd. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Een transformatiefunctie die op elk element wordt toegepast. |

### Retourwaarde

De minimale waarde in de reeks.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) methode

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Zie ook

* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)