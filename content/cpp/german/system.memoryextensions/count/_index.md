---
title: Count()
second_title: Aspose.Slides für C++ API Referenz
description: Zählt das Auftreten eines Werts in einem schreibgeschützten Span.
type: docs
weight: 118
url: /de/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) Funktion


Zählt das Auftreten eines Werts in einem schreibgeschützten Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to count |

### Rückgabewert

Die Anzahl, wie oft value im span vorkommt

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion


Zählt das Auftreten eines Spans innerhalb eines anderen schreibgeschützten Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to count occurrences of |

### Rückgabewert

Die Anzahl, wie oft value im span vorkommt

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) Funktion


Zählt das Auftreten eines einzelnen Werts in einem Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to count occurrences of |

### Rückgabewert

Die Anzahl der Vorkommen des Werts im span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion


Zählt das Auftreten eines ReadOnlySpan<T> in einem Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to count occurrences of |

### Rückgabewert

Die Anzahl der Vorkommen des value span im target span

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)