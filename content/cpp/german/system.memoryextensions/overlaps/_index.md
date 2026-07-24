---
title: Overlaps()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob zwei ReadOnlySpans im Speicher überlappen, ohne den Offset zu berechnen.
type: docs
weight: 274
url: /de/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Bestimmt, ob zwei ReadOnlySpans im Speicher überlappen, ohne den Offset zu berechnen.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der erste Span, der auf Überlappung geprüft wird |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zweite Span, der auf Überlappung geprüft wird |

### Rückgabewert

true, wenn die Spans gemeinsam genutzte Speicherorte haben, sonst false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Bestimmt, ob ein [Span](../../system/span/) und [ReadOnlySpan](../../system/readonlyspan/) im Speicher überlappen, ohne den Offset zu berechnen.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der [Span](../../system/span/) zur Überprüfung auf Überlappung |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der [ReadOnlySpan](../../system/readonlyspan/) zur Überprüfung auf Überlappung |

### Rückgabewert

true, wenn die Spans gemeinsam genutzte Speicherorte haben, sonst false

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) Funktion

Bestimmt, ob zwei ReadOnlySpans im Speicher überlappen und den Offset berechnet.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der erste Span, der auf Überlappung geprüft wird |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zweite Span, der auf Überlappung geprüft wird |
| elementOffset | **int32_t**\& | Ausgabeparameter, der den Offset zwischen den Spans erhält, falls sie überlappen |

### Rückgabewert

true, wenn die Spans gemeinsam genutzte Speicherorte haben, sonst false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) Funktion

Bestimmt, ob ein [Span](../../system/span/) und [ReadOnlySpan](../../system/readonlyspan/) im Speicher überlappen und den Offset berechnet.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der [Span](../../system/span/) zur Überprüfung auf Überlappung |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der [ReadOnlySpan](../../system/readonlyspan/) zur Überprüfung auf Überlappung |
| elementOffset | **int32_t**\& | Ausgabeparameter, der den Offset zwischen den Spans erhält, falls sie überlappen |

### Rückgabewert

true, wenn die Spans gemeinsam genutzte Speicherorte haben, sonst false

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)