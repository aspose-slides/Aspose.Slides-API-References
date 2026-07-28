---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Znajduje ostatnie wystąpienie dowolnego elementu poza określonym zakresem w spanie.
type: docs
weight: 248
url: /pl/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu poza określonym zakresem w spanie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica zakresu (włącznie) |
| highInclusive | const T\& | Górna granica zakresu (włącznie) |

### Wartość zwracana

Indeks (liczony od zera) ostatniego elementu spoza zakresu lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funkcja


Znajduje ostatnie wystąpienie dowolnego elementu poza określonym zakresem w modyfikowalnym spanie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w spanie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica zakresu (włącznie) |
| highInclusive | const T\& | Górna granica zakresu (włącznie) |

### Wartość zwracana

Indeks (liczony od zera) ostatniego elementu spoza zakresu lub -1, jeśli nie znaleziono

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)