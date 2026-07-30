---
title: IndexOfAnyInRange()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Najde index prvního prvku, který je v zadaném rozsahu v ReadOnlySpan<T>
type: docs
weight: 196
url: /cs/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Najde index prvního prvku, který se nachází v zadaném rozsahu v ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template parameters

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez rozsahu (včetně) |
| highInclusive | const T\& | Horní mez rozsahu (včetně) |

### Return Value

Nulový index prvního prvku v rozsahu, nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Najde index prvního prvku, který se nachází v zadaném rozsahu ve Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Template parameters

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rozsah, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez rozsahu (včetně) |
| highInclusive | const T\& | Horní mez rozsahu (včetně) |

### Return Value

Nulový index prvního prvku v rozsahu, nebo -1, pokud nebyl nalezen

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)