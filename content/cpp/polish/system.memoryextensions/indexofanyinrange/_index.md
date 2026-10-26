---
title: IndexOfAnyInRange()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Znajduje indeks pierwszego elementu, który znajduje się w określonym przedziale w ReadOnlySpan<T>
type: docs
weight: 196
url: /pl/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkcja

Znajduje indeks pierwszego elementu, który znajduje się w określonym przedziale w ReadOnlySpan\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w przedziale |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span do przeszukania |
| lowInclusive | const T\& | Dolna granica przedziału (włącznie) |
| highInclusive | const T\& | Górna granica przedziału (włącznie) |

### Wartość zwracana

Zero-indeksowy indeks pierwszego elementu w przedziale lub -1, jeśli nie został znaleziony

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) funkcja

Znajduje indeks pierwszego elementu, który znajduje się w określonym przedziale w Span\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w przedziale |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span do przeszukania |
| lowInclusive | const T\& | Dolna granica przedziału (włącznie) |
| highInclusive | const T\& | Górna granica przedziału (włącznie) |

### Wartość zwracana

Zero-indeksowy indeks pierwszego elementu w przedziale lub -1, jeśli nie został znaleziony

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)