---
title: IndexOfAnyInRange()
second_title: Aspose.Slides für C++ API Referenz
description: Findet den Index des ersten Elements, das innerhalb des angegebenen Bereichs in einem ReadOnlySpan<T> liegt
type: docs
weight: 196
url: /de/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion


Findet den Index des ersten Elements, das innerhalb des angegebenen Bereichs in einem ReadOnlySpan<T> liegt

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (einschließlich) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (einschließlich) |

### Rückgabewert

Der nullbasierte Index des ersten Elements im Bereich oder -1, falls nicht gefunden

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) Funktion


Findet den Index des ersten Elements, das innerhalb des angegebenen Bereichs in einem Span<T> liegt

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende Span |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (einschließlich) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (einschließlich) |

### Rückgabewert

Der nullbasierte Index des ersten Elements im Bereich oder -1, falls nicht gefunden

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)