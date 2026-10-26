---
title: SequenceCompareTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergelijkt twee ReadOnlySpans lexicografisch.
type: docs
weight: 313
url: /nl/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Vergelijkt twee ReadOnlySpans lexicografisch.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De eerste span om te vergelijken |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De tweede span om te vergelijken |

### Retourwaarde

- 1 als span < other, 0 als span == other, 1 als span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) functie

Vergelijkt een [Span](../../system/span/) en [ReadOnlySpan](../../system/readonlyspan/) lexicografisch.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | De [Span](../../system/span/) om te vergelijken |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De [ReadOnlySpan](../../system/readonlyspan/) om te vergelijken |

### Retourwaarde

- 1 als span < other, 0 als span == other, 1 als span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) functie

Vergelijkt een [ReadOnlySpan](../../system/readonlyspan/) en [Span](../../system/span/) lexicografisch.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type elementen in de spans |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | De [ReadOnlySpan](../../system/readonlyspan/) om te vergelijken |
| other | const [Span](../../system/span/)\<T\>\& | De [Span](../../system/span/) om te vergelijken |

### Retourwaarde

- 1 als span < other, 0 als span == other, 1 als span > other

## Zie ook

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Naamruimte [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)