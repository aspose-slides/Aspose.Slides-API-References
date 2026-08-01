---
title: PickPivotAndPartition()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert een pivot en partitioneert sleutel-waardeparen voor quicksort.
type: docs
weight: 105
url: /nl/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) functie

Selecteert pivot en partitioneert sleutel-waardeparen voor quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type sleutels |
| TValue | Het type waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Het bereik van sleutels om te partitioneren |
| values | [Span](../../system/span/)\<TValue\>\& | Het bereik van waarden om te partitioneren |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) functie voor sleutels |

### Retourwaarde

De pivot-index na partitionering

## Zie ook

* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)