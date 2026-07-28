---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Znajduje ostatnie wystąpienie dowolnego elementu w określonym zakresie w obrębie span.
type: docs
weight: 261
url: /pl/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Znajduje ostatnie wystąpienie dowolnego elementu w określonym zakresie w obrębie span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w segmencie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Segment, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica zakresu (włącznie) |
| highInclusive | const T\& | Górna granica zakresu (włącznie) |

### Wartość zwracana

Zero-indeksowa pozycja ostatniego elementu w zakresie lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Znajduje ostatnie wystąpienie dowolnego elementu w określonym zakresie w obrębie mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w segmencie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Segment, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica zakresu (włącznie) |
| highInclusive | const T\& | Górna granica zakresu (włącznie) |

### Wartość zwracana

Zero-indeksowa pozycja ostatniego elementu w zakresie lub -1, jeśli nie znaleziono

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)