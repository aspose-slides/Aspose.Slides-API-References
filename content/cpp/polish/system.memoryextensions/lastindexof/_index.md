---
title: LastIndexOf()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Znajduje ostatnie wystąpienie sekwencji w obrębie zakresu.
type: docs
weight: 209
url: /pl/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Znajduje ostatnie wystąpienie sekwencji w obrębie zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy wyszukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekwencja do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia (liczony od zera) lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) funkcja


Znajduje ostatnie wystąpienie pojedynczej wartości w obrębie zakresu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy wyszukać |
| value | const T\& | Wartość do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia (liczony od zera) lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Znajduje ostatnie wystąpienie sekwencji w modyfikowalnym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy wyszukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekwencja do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia (liczony od zera) lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) funkcja


Znajduje ostatnie wystąpienie pojedynczej wartości w modyfikowalnym zakresie.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy wyszukać |
| value | const T\& | Wartość do wyszukania |

### Wartość zwracana

Indeks ostatniego wystąpienia (liczony od zera) lub -1, jeśli nie znaleziono

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkcja


Znajduje ostatnie wystąpienie wartości w zakresie przy użyciu określonego porównania ciągów.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres, w którym należy wyszukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Wartość do wyszukania |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porównania ciągów do wykonania |

### Wartość zwracana

Indeks ostatniego wystąpienia (liczony od zera) lub -1, jeśli nie znaleziono

## Zobacz także

* Enum [StringComparison](../../system/stringcomparison/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)