---
title: EqualityComparerAdapter
second_title: Aspose.Slides voor C++ API-referentie
description: "Adapter die het mogelijk maakt IEqualityComparer te gebruiken met STL-achtige collecties en algoritmen. Gebruikt IEqualityComparer, indien ingesteld. Indien niet ingesteld, gebruikt operator ==, Object::Equals of T::Equals, afhankelijk van wat beschikbaar is."
type: docs
weight: 664
url: /nl/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adapter die het mogelijk maakt [IEqualityComparer](../iequalitycomparer/) te gebruiken met STL-achtige collecties en algoritmes. Gebruikt [IEqualityComparer](../iequalitycomparer/), indien ingesteld. Indien niet ingesteld, gebruikt operator ==, [Object::Equals](../../system/object/equals/) of T::Equals, afhankelijk van wat beschikbaar is.

```cpp
template<class T>class EqualityComparerAdapter
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type dat wordt vergeleken. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Creëert een adapter die geen comparator gebruikt. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Creëert een adapter met de gegeven comparator. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Vergelijkt twee objecten. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Stelt de comparator in. |

## Zie ook

* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)