---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides für C++ API-Referenz
description: Findet das letzte Vorkommen eines beliebigen Elements außerhalb des angegebenen Bereichs innerhalb eines Spans.
type: docs
weight: 248
url: /de/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines beliebigen Elements außerhalb des angegebenen Bereichs innerhalb eines Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zu durchsuchende Span |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (einschließlich) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (einschließlich) |

### Rückgabewert

Der nullbasierte Index des letzten Elements außerhalb des Bereichs oder -1, wenn nicht gefunden

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) Funktion

Findet das letzte Vorkommen eines beliebigen Elements außerhalb des angegebenen Bereichs innerhalb eines veränderbaren Spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente im Span |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der zu durchsuchende Span |
| lowInclusive | const T\& | Die untere Grenze des Bereichs (einschließlich) |
| highInclusive | const T\& | Die obere Grenze des Bereichs (einschließlich) |

### Rückgabewert

Der nullbasierte Index des letzten Elements außerhalb des Bereichs oder -1, wenn nicht gefunden

## Siehe auch

* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)