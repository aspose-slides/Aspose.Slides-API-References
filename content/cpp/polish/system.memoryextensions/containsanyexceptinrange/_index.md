---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy ReadOnlySpan zawiera jakikolwiek element poza określonym zakresem.
type: docs
weight: 79
url: /pl/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkcja


Sprawdza, czy ReadOnlySpan zawiera jakikolwiek element poza określonym zakresem.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w span (musi być porównywalny) |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica (włącznie) |
| highInclusive | const T\& | Górna granica (włącznie) |

### Wartość zwracana

true, jeśli zostanie znaleziony jakikolwiek element poza zakresem, w przeciwnym razie false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funkcja


Sprawdza, czy mutable span zawiera jakikolwiek element poza określonym zakresem.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w span (musi być porównywalny) |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica (włącznie) |
| highInclusive | const T\& | Górna granica (włącznie) |

### Wartość zwracana

true, jeśli zostanie znaleziony jakikolwiek element poza zakresem, w przeciwnym razie false

## Zobacz również

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)