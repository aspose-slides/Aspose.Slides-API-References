---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Najde index prvního prvku, který je mimo zadaný rozsah v ReadOnlySpan<T>
type: docs
weight: 183
url: /cs/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce

Najde index prvního prvku, který je mimo zadaný rozsah v ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| lowInclusive | const T\& | dolní mez rozsahu (včetně) |
| highInclusive | const T\& | horní mez rozsahu (včetně) |

### Návratová hodnota

index začínající od nuly prvního prvku mimo rozsah nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funkce

Najde index prvního prvku, který je mimo zadaný rozsah v Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| lowInclusive | const T\& | dolní mez rozsahu (včetně) |
| highInclusive | const T\& | horní mez rozsahu (včetně) |

### Návratová hodnota

index začínající od nuly prvního prvku mimo rozsah nebo -1, pokud nebyl nalezen

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)