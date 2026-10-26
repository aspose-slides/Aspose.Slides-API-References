---
title: BinarySearch()
second_title: Aspose.Slides für C++ API Referenz
description: Führt eine binäre Suche in einem sortierten Span aus.
type: docs
weight: 14
url: /de/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) Funktion

Führt eine binäre Suche in einem sortierten Span durch.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Rückgabewert

[Index](../../system/index/) des gefundenen Elements oder bitweise Komplement des Einfügepunktes, falls nicht gefunden

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) Funktion

Führt eine binäre Suche in einem sortierten Span mit einem benutzerdefinierten Comparer durch.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Rückgabewert

[Index](../../system/index/) des gefundenen Elements oder bitweise Komplement des Einfügepunktes, falls nicht gefunden

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) Funktion

Führt eine binäre Suche in einem veränderbaren sortierten Span durch.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Rückgabewert

[Index](../../system/index/) des gefundenen Elements oder bitweise Komplement des Einfügepunktes, falls nicht gefunden

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) Funktion

Führt eine binäre Suche in einem veränderbaren sortierten Span mit einem benutzerdefinierten Comparer durch.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Rückgabewert

[Index](../../system/index/) des gefundenen Elements oder bitweise Komplement des Einfügepunktes, falls nicht gefunden

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)