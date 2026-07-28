---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Znajduje indeks pierwszego elementu, który znajduje się poza określonym zakresem w ReadOnlySpan<T>
type: docs
weight: 183
url: /pl/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Znajduje indeks pierwszego elementu znajdującego się poza określonym zakresem w ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w przedziale |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Przedział, w którym należy wyszukać |
| lowInclusive | const T\& | Dolna granica zakresu (włącznie) |
| highInclusive | const T\& | Górna granica zakresu (włącznie) |

### Wartość zwracana

Indeks zerowy pierwszego elementu spoza zakresu lub -1, jeśli nie znaleziono

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

Znajduje indeks pierwszego elementu znajdującego się poza określonym zakresem w Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w przedziale |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Przedział, w którym należy wyszukać |
| lowInclusive | const T\& | Dolna granica zakresu (włącznie) |
| highInclusive | const T\& | Górna granica zakresu (włącznie) |

### Wartość zwracana

Indeks zerowy pierwszego elementu spoza zakresu lub -1, jeśli nie znaleziono

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)