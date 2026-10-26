---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda read-only span obsahuje jakýkoli prvek mimo zadaný rozsah.
type: docs
weight: 79
url: /cs/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce

Kontroluje, zda read-only span obsahuje jakýkoli prvek mimo zadaný rozsah.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu (musí být porovnatelný) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez (včetně) |
| highInclusive | const T\& | Horní mez (včetně) |

### Návratová hodnota

true pokud je nalezen jakýkoli prvek mimo rozsah, false jinak

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) funkce

Kontroluje, zda mutable span obsahuje jakýkoli prvek mimo zadaný rozsah.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu (musí být porovnatelný) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable rozsah, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez (včetně) |
| highInclusive | const T\& | Horní mez (včetně) |

### Návratová hodnota

true pokud je nalezen jakýkoli prvek mimo rozsah, false jinak

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Prostor názvů [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)