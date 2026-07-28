---
title: Overlaps()
second_title: Odwołanie API Aspose.Slides dla C++
description: Określa, czy dwa ReadOnlySpan-y zachodzą na siebie w pamięci bez obliczania offsetu.
type: docs
weight: 274
url: /pl/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Określa, czy dwa ReadOnlySpan-y zachodzą na siebie w pamięci bez obliczania offsetu.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy zakres do sprawdzenia nachodzenia |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi zakres do sprawdzenia nachodzenia |

### Wartość zwracana

true, jeśli zakresy dzielą jakiekolwiek wspólne lokalizacje pamięci, false w przeciwnym razie

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja

Określa, czy [Span](../../system/span/) i [ReadOnlySpan](../../system/readonlyspan/) zachodzą na siebie w pamięci bez obliczania offsetu.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) do sprawdzenia nachodzenia |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) do sprawdzenia nachodzenia |

### Wartość zwracana

true, jeśli zakresy dzielą jakiekolwiek wspólne lokalizacje pamięci, false w przeciwnym razie

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funkcja

Określa, czy dwa ReadOnlySpan-y zachodzą na siebie w pamięci i oblicza offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Pierwszy zakres do sprawdzenia nachodzenia |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Drugi zakres do sprawdzenia nachodzenia |
| elementOffset | **int32_t**\& | Parametr wyjściowy, który otrzymuje offset między zakresami, jeśli zachodzą na siebie |

### Wartość zwracana

true, jeśli zakresy dzielą jakiekolwiek wspólne lokalizacje pamięci, false w przeciwnym razie

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) funkcja

Określa, czy [Span](../../system/span/) i [ReadOnlySpan](../../system/readonlyspan/) zachodzą na siebie w pamięci i oblicza offset.

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) do sprawdzenia nachodzenia |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) do sprawdzenia nachodzenia |
| elementOffset | **int32_t**\& | Parametr wyjściowy, który otrzymuje offset między zakresami, jeśli zachodzą na siebie |

### Wartość zwracana

true, jeśli zakresy dzielą jakiekolwiek wspólne lokalizacje pamięci, false w przeciwnym razie

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)