---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob ein schreibgeschützter Span ein Element außerhalb des angegebenen Bereichs enthält.
type: docs
weight: 79
url: /de/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Überprüft, ob ein schreibgeschützter Span ein Element außerhalb des angegebenen Bereichs enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span (muss vergleichbar sein) |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| lowInclusive | const T\& | Die untere Schranke (inklusive) |
| highInclusive | const T\& | Die obere Schranke (inklusive) |

### Rückgabewert

true, wenn ein Element außerhalb des Bereichs gefunden wird, sonst false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Überprüft, ob ein veränderbarer Span ein Element außerhalb des angegebenen Bereichs enthält.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template-Parameter

| Parameter | Description |
| --- | --- |
| T | Der Typ der Elemente im Span (muss vergleichbar sein) |

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der veränderbare Span, in dem gesucht wird |
| lowInclusive | const T\& | Die untere Schranke (inklusive) |
| highInclusive | const T\& | Die obere Schranke (inklusive) |

### Rückgabewert

true, wenn ein Element außerhalb des Bereichs gefunden wird, sonst false

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)