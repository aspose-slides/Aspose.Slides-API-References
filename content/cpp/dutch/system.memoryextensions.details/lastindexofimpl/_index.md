---
title: LastIndexOfImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt de laatste index van een waarde in een span.
type: docs
weight: 14
url: /nl/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) functie

Zoekt de laatste index van een waarde in een span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type van elementen in span |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) om te zoeken |
| length | **int32_t** | Lengte om in te zoeken |
| value | const T\& | Waarde om te vinden |

### Retourwaarde

Laatste index van de waarde, of -1 als niet gevonden

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Naamruimte [System::MemoryExtensions::Details](../)
* Bibliotheek [Aspose.Slides](../../)