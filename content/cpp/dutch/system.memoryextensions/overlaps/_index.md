---
title: Overlaps()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of twee ReadOnlySpans overlappen in het geheugen zonder de offset te berekenen.
type: docs
weight: 274
url: /nl/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Bepaalt of twee ReadOnlySpans overlappen in het geheugen zonder de offset te berekenen.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De eerste span om te controleren op overlappen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De tweede span om te controleren op overlappen |

### Retourwaarde

true als de spans gemeenschappelijke geheugenlocaties delen, false anders

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie


Bepaalt of een [Span](../../system/span/) en [ReadOnlySpan](../../system/readonlyspan/) overlappen in het geheugen zonder de offset te berekenen.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De [Span](../../system/span/) om te controleren op overlappen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De [ReadOnlySpan](../../system/readonlyspan/) om te controleren op overlappen |

### Retourwaarde

true als de spans gemeenschappelijke geheugenlocaties delen, false anders

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) functie


Bepaalt of twee ReadOnlySpans overlappen in het geheugen en berekent de offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De eerste span om te controleren op overlappen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De tweede span om te controleren op overlappen |
| elementOffset | **int32_t**\& | Output-parameter die de offset tussen de spans ontvangt indien ze overlappen |

### Retourwaarde

true als de spans gemeenschappelijke geheugenlocaties delen, false anders

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) functie


Bepaalt of een [Span](../../system/span/) en [ReadOnlySpan](../../system/readonlyspan/) overlappen in het geheugen en berekent de offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De [Span](../../system/span/) om te controleren op overlappen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De [ReadOnlySpan](../../system/readonlyspan/) om te controleren op overlappen |
| elementOffset | **int32_t**\& | Output-parameter die de offset tussen de spans ontvangt indien ze overlappen |

### Retourwaarde

true als de spans gemeenschappelijke geheugenlocaties delen, false anders

## Zie ook

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)