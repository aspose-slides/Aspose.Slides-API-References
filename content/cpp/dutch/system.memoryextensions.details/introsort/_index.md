---
title: IntroSort()
second_title: Aspose.Slides voor C++ API-referentie
description: Interne implementatie van het introsort-algoritme voor sleutel-waardeparen.
type: docs
weight: 40
url: /nl/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) functie

Interne implementatie van het introsort-algoritme voor sleutel-waardeparen.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TKey | Het type van sleutels |
| TValue | Het type van waarden |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Het bereik van sleutels om te sorteren |
| values | [Span](../../system/span/)\<TValue\>\& | Het bereik van waarden om te sorteren |
| depthLimit | **int32_t** | Maximale recursiediepte vóór overschakeling naar heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) functie voor sleutels |

## Zie ook

* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)