---
title: SequenceCompareTo()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två ReadOnlySpans lexikografiskt.
type: docs
weight: 313
url: /sv/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion

Jämför två ReadOnlySpans lexikografiskt.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den första spannen att jämföra |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den andra spannen att jämföra |

### Returvärde

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion

Jämför en [Span](../../system/span/) och [ReadOnlySpan](../../system/readonlyspan/) lexikografiskt.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Den [Span](../../system/span/) att jämföra |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den [ReadOnlySpan](../../system/readonlyspan/) att jämföra |

### Returvärde

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funktion

Jämför en [ReadOnlySpan](../../system/readonlyspan/) och [Span](../../system/span/) lexikografiskt.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Den [ReadOnlySpan](../../system/readonlyspan/) att jämföra |
| other | const [Span](../../system/span/)\<T\>\& | Den [Span](../../system/span/) att jämföra |

### Returvärde

- 1 if span < other, 0 if span == other, 1 if span > other

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)