---
title: SequenceCompareTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta due ReadOnlySpans lessicograficamente.
type: docs
weight: 313
url: /it/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Confronta due ReadOnlySpans lessicograficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parametri del template

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il primo span da confrontare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il secondo span da confrontare |

### Valore di ritorno

- 1 se span < other, 0 se span == other, 1 se span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funzione

Confronta un [Span](../../system/span/) e [ReadOnlySpan](../../system/readonlyspan/) lessicograficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parametri del template

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Il [Span](../../system/span/) da confrontare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il [ReadOnlySpan](../../system/readonlyspan/) da confrontare |

### Valore di ritorno

- 1 se span < other, 0 se span == other, 1 se span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funzione

Confronta un [ReadOnlySpan](../../system/readonlyspan/) e [Span](../../system/span/) lessicograficamente.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Parametri del template

| Parameter | Description |
| --- | --- |
| T | Il tipo di elementi negli span |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Il [ReadOnlySpan](../../system/readonlyspan/) da confrontare |
| other | const [Span](../../system/span/)\<T\>\& | Il [Span](../../system/span/) da confrontare |

### Valore di ritorno

- 1 se span < other, 0 se span == other, 1 se span > other

## Vedi anche

* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Libreria [Aspose.Slides](../../)