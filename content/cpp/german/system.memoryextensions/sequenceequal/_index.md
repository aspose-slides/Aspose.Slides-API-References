---
title: SequenceEqual()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob zwei ReadOnlySpans identische Elemente in derselben Reihenfolge enthalten.
type: docs
weight: 326
url: /de/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Bestimmt, ob zwei ReadOnlySpans identische Elemente in derselben Reihenfolge enthalten.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der erste Span zum Vergleichen |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zweite Span zum Vergleichen |

### Rückgabewert

true wenn die Spans dieselbe Länge haben und alle Elemente gleich sind, false andernfalls

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) Funktion

Bestimmt, ob ein [Span](../../system/span/) und [ReadOnlySpan](../../system/readonlyspan/) identische Elemente in derselben Reihenfolge enthalten.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der [Span](../../system/span/) zum Vergleichen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der [ReadOnlySpan](../../system/readonlyspan/) zum Vergleichen |

### Rückgabewert

true wenn die Spans dieselbe Länge haben und alle Elemente gleich sind, false andernfalls

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) Funktion

Bestimmt, ob zwei ReadOnlySpans gleiche Elemente mithilfe eines benutzerdefinierten Vergleichers enthalten.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |
| TComparer | Der Typ des Vergleichsobjekts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der erste Span zum Vergleichen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der zweite Span zum Vergleichen |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart-Pointer zum Vergleichsobjekt für den Elementvergleich |

### Rückgabewert

true wenn die Spans dieselbe Länge haben und der Comparer alle Elemente als gleich ansieht, false andernfalls

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) Funktion

Bestimmt, ob ein [Span](../../system/span/) und [ReadOnlySpan](../../system/readonlyspan/) gleiche Elemente mithilfe eines benutzerdefinierten Vergleichers enthalten.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in den Spans |
| TComparer | Der Typ des Vergleichsobjekts |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Der [Span](../../system/span/) zum Vergleichen |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Der [ReadOnlySpan](../../system/readonlyspan/) zum Vergleichen |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart-Pointer zum Vergleichsobjekt für den Elementvergleich |

### Rückgabewert

true wenn die Spans dieselbe Länge haben und der Comparer alle Elemente als gleich ansieht, false andernfalls

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)