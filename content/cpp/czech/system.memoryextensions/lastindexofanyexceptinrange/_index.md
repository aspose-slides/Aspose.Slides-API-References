---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vyhledá poslední výskyt libovolného prvku mimo určený rozsah ve spanu.
type: docs
weight: 248
url: /cs/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce

Najde poslední výskyt libovolného prvku mimo specifikovaný rozsah v rámci spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez rozsahu (včetně) |
| highInclusive | const T\& | Horní mez rozsahu (včetně) |

### Návratová hodnota

Nulový index posledního prvku mimo rozsah, nebo -1 pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funkce

Najde poslední výskyt libovolného prvku mimo specifikovaný rozsah v mutovatelném spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez rozsahu (včetně) |
| highInclusive | const T\& | Horní mez rozsahu (včetně) |

### Návratová hodnota

Nulový index posledního prvku mimo rozsah, nebo -1 pokud nebyl nalezen

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)