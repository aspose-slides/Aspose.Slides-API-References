---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet den Index des ersten Elements, das außerhalb des angegebenen Bereichs in einem ReadOnlySpan<T> liegt
type: docs
weight: 183
url: /de/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion


Findet den Index des ersten Elements, das außerhalb des angegebenen Bereichs in einem ReadOnlySpan\<T\> liegt

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (inklusive) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (inklusive) |

### Rückgabewert

Der nullbasierte Index des ersten Elements außerhalb des Bereichs oder -1, wenn nicht gefunden

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) Funktion


Findet den Index des ersten Elements, das außerhalb des angegebenen Bereichs in einem Span\<T\> liegt

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (inklusive) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (inklusive) |

### Rückgabewert

Der nullbasierte Index des ersten Elements außerhalb des Bereichs oder -1, wenn nicht gefunden

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)