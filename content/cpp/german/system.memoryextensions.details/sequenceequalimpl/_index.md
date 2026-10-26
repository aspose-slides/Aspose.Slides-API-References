---
title: SequenceEqualImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob zwei Spannen ab den angegebenen Positionen gleich sind.
type: docs
weight: 27
url: /de/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) function

Überprüft, ob zwei Spannen ab den angegebenen Positionen gleich sind.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ der Elemente in den Spannen |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Erster Span |
| start | const **int32_t** | Startindex im ersten Span |
| length | **int32_t** | Anzahl der zu vergleichenden Elemente |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zweiter Span |

### Rückgabewert

true, wenn die angegebenen Bereiche gleich sind, sonst false

## Siehe auch

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)