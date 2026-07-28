---
title: SequenceCompareTo()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Porównuje dwa ReadOnlySpans leksykograficznie.
type: docs
weight: 313
url: /pl/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Porównuje dwa ReadOnlySpans leksykograficznie.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy span do porównania |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi span do porównania |

### Wartość zwracana

- 1 jeśli span < other, 0 jeśli span == other, 1 jeśli span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Porównuje [Span](../../system/span/) i [ReadOnlySpan](../../system/readonlyspan/) leksykograficznie.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) do porównania |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) do porównania |

### Wartość zwracana

- 1 jeśli span < other, 0 jeśli span == other, 1 jeśli span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funkcja

Porównuje [ReadOnlySpan](../../system/readonlyspan/) i [Span](../../system/span/) leksykograficznie.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) do porównania |
| other | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) do porównania |

### Wartość zwracana

- 1 jeśli span < other, 0 jeśli span == other, 1 jeśli span > other

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)