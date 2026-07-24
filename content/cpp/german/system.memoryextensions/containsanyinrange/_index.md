---
title: ContainsAnyInRange()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein schreibgeschützter Span ein Element innerhalb des angegebenen Bereichs enthält.
type: docs
weight: 92
url: /de/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion

Überprüft, ob ein schreibgeschützter Span ein Element innerhalb des angegebenen Bereichs enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span (muss vergleichbar sein) |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| lowInclusive | const T\& | Die untere Grenze (inklusive) |
| highInclusive | const T\& | Die obere Grenze (inklusive) |

### Return Value

true, wenn ein Element innerhalb des Bereichs gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) Funktion

Überprüft, ob ein veränderbarer Span ein Element innerhalb des angegebenen Bereichs enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span (muss vergleichbar sein) |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der veränderbare Span, in dem gesucht wird |
| lowInclusive | const T\& | Die untere Grenze (inklusive) |
| highInclusive | const T\& | Die obere Grenze (inklusive) |

### Return Value

true, wenn ein Element innerhalb des Bereichs gefunden wird, sonst false

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)