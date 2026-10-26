---
title: ContainsAnyInRange()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy odczytywalny span zawiera dowolny element w określonym zakresie.
type: docs
weight: 92
url: /pl/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkcja

Sprawdza, czy odczytywalny span zawiera jakikolwiek element w określonym zakresie.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ elementów w spanie (musi być porównywalny) |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica (włącznie) |
| highInclusive | const T\& | Górna granica (włącznie) |

### Wartość zwracana

true, jeśli znaleziono dowolny element w zakresie, w przeciwnym razie false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) funkcja

Sprawdza, czy modyfikowalny span zawiera jakikolwiek element w określonym zakresie.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| T | Typ elementów w spanie (musi być porównywalny) |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Modyfikowalny span, w którym należy szukać |
| lowInclusive | const T\& | Dolna granica (włącznie) |
| highInclusive | const T\& | Górna granica (włącznie) |

### Wartość zwracana

true, jeśli znaleziono dowolny element w zakresie, w przeciwnym razie false

## Zobacz także

* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)