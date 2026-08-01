---
title: TrueForAll()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of alle elementen in de opgegeven array voldoen aan de door het opgegeven predicaat gedefinieerde voorwaarden.
type: docs
weight: 677
url: /nl/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) methode

Bepaalt of alle elementen in de opgegeven array voldoen aan de door de opgegeven predicaat gedefinieerde voorwaarden.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elementen die moeten worden vergeleken met de voorwaarden |
| match | [System::Predicate](../../predicate/)\<T\> | Een predicaat dat de voorwaarden definieert waaraan array-elementen moeten voldoen |

### Retourwaarde

true als alle elementen van de array arr voldoen aan de door predicaat match gedefinieerde voorwaarden, anders false

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)