---
title: BinarySearchImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Algemene implementatie van binaire zoekopdracht.
type: docs
weight: 118
url: /nl/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) functie

Algemene implementatie van binaire zoekopdracht.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type of elements in span |
| TValue | Type of value to search for |
| TCompareFunc | Function type for comparison |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De te doorzoeken span |
| value | const TValue\& | De te zoeken waarde |
| compareFunc | TCompareFunc | Functie die de waarde vergelijkt met het span-element en een **int32_t** (-1, 0, 1) retourneert |

### Retourwaarde

[Index](../../system/index/) van gevonden element of bitwise complement van insertiepunt

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Naamruimte [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)