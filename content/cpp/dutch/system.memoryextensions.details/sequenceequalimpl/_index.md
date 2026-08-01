---
title: SequenceEqualImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of twee spans gelijk zijn, beginnend vanaf de opgegeven posities.
type: docs
weight: 27
url: /nl/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) functie

Controleert of twee spans gelijk zijn, beginnend vanaf de opgegeven posities.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van elementen in spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Eerste span |
| start | const **int32_t** | Beginindex in eerste span |
| length | **int32_t** | Aantal elementen om te vergelijken |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Tweede span |

### Returnwaarde

true als de opgegeven bereiken gelijk zijn, anders false

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Naamruimte [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)