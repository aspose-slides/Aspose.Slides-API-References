---
title: LINQ_Max()
second_title: Aspose.Slides voor C++ API-referentie
description: Roept een transformatiefunctie aan op elk element van een generieke reeks en retourneert de maximale resulterende waarde.
type: docs
weight: 352
url: /nl/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) methode

Roep een transformatiefunctie aan op elk element van een algemene reeks en retourneert de maximale resulterende waarde.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
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

De maximale waarde in de reeks.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) methode

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Zie ook

* Klasse [Func](../../../system/func/)
* Klasse [IEnumerable](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)