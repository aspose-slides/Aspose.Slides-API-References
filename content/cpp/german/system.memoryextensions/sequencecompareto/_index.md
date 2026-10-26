---
title: SequenceCompareTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei ReadOnlySpans lexikografisch.
type: docs
weight: 313
url: /de/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Vergleicht zwei ReadOnlySpans lexikografisch.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der erste Span zum Vergleichen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zweite Span zum Vergleichen |

### Rückgabewert

- 1 wenn span < other, 0 wenn span == other, 1 wenn span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Vergleicht ein [Span](../../system/span/) und [ReadOnlySpan](../../system/readonlyspan/) lexikografisch.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der [Span](../../system/span/) zum Vergleichen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der [ReadOnlySpan](../../system/readonlyspan/) zum Vergleichen |

### Rückgabewert

- 1 wenn span < other, 0 wenn span == other, 1 wenn span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) Funktion


Vergleicht ein [ReadOnlySpan](../../system/readonlyspan/) und [Span](../../system/span/) lexikografisch.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der [ReadOnlySpan](../../system/readonlyspan/) zum Vergleichen |
| other | const [Span](../../system/span/)\<T\>\& | Der [Span](../../system/span/) zum Vergleichen |

### Rückgabewert

- 1 wenn span < other, 0 wenn span == other, 1 wenn span > other

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)