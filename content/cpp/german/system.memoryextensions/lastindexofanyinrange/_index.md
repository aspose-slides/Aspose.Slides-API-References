---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet das letzte Vorkommen eines beliebigen Elements im angegebenen Bereich in einem Span.
type: docs
weight: 261
url: /de/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines beliebigen Elements innerhalb des angegebenen Bereichs in einem Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der Span, in dem gesucht wird |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (einschließlich) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (einschließlich) |

### Rückgabewert

Der nullbasierte Index des letzten Elements im Bereich oder -1, falls nicht gefunden.

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines beliebigen Elements innerhalb des angegebenen Bereichs in einem veränderbaren Span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der Span, in dem gesucht wird |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (einschließlich) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (einschließlich) |

### Rückgabewert

Der nullbasierte Index des letzten Elements im Bereich oder -1, falls nicht gefunden.

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)