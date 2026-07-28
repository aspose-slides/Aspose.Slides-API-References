---
title: Contains()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Sprawdza, czy odczytywalny span zawiera określoną wartość.
type: docs
weight: 40
url: /pl/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) funkcja


Sprawdza, czy odczytywalny span zawiera określoną wartość.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to search for |

### Wartość zwracana

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) funkcja


Sprawdza, czy modyfikowalny span zawiera określoną wartość.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | The type of elements in the span |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span to search in |
| value | const T\& | The value to search for |

### Wartość zwracana

true if value is found in span, false otherwise

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkcja


Sprawdza, czy span znaków zawiera inny span znaków przy określonych zasadach porównania.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### Wartość zwracana

true if value is found in span, false otherwise

## Zobacz również

* Wyliczenie [StringComparison](../../system/stringcomparison/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)