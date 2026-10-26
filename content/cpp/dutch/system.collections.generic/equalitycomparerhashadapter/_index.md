---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides voor C++ API-referentie
description: Adapter om IEqualityComparer te gebruiken voor hashing. Gebruikt een comparator-object, indien ingesteld; anders wordt de beschikbare hash-methode gebruikt die is geselecteerd met de DictionaryHashSelector struct.
type: docs
weight: 677
url: /nl/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

Adapter om [IEqualityComparer](../iequalitycomparer/) te gebruiken voor hashing. Gebruikt een comparator-object, indien ingesteld; anders wordt de beschikbare hash-methode gebruikt die is geselecteerd met de [DictionaryHashSelector](../dictionaryhashselector/) struct.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Hashed | type. |

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Maakt een adapter zonder comparator om te gebruiken. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Maakt een adapter met de opgegeven comparator om te gebruiken. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Berekent de hash-waarde. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Stelt de te gebruiken comparator in. |

## Zie ook

* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)