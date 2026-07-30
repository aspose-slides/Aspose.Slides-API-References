---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vyhledá poslední výskyt libovolného prvku v určeném rozsahu ve spanu.
type: docs
weight: 261
url: /cs/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce

Najde poslední výskyt libovolného prvku v určeném rozsahu ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| lowInclusive | const T\& | Dolní hranice rozsahu (včetně) |
| highInclusive | const T\& | Horní hranice rozsahu (včetně) |

### Návratová hodnota

Nulový index posledního prvku v rozsahu, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) funkce

Najde poslední výskyt libovolného prvku v určeném rozsahu v mutovatelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| lowInclusive | const T\& | Dolní hranice rozsahu (včetně) |
| highInclusive | const T\& | Horní hranice rozsahu (včetně) |

### Návratová hodnota

Nulový index posledního prvku v rozsahu, nebo -1 pokud nebyl nalezen

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)