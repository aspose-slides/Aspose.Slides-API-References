---
title: ContainsAnyInRange()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Kontroluje, zda pouze pro čtení span obsahuje libovolný prvek v určeném rozsahu.
type: docs
weight: 92
url: /cs/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) funkce


Kontroluje, zda pouze pro čtení span obsahuje libovolný prvek v určeném rozsahu.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spasmu (musí být porovnatelné) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez (včetně) |
| highInclusive | const T\& | Horní mez (včetně) |

### Návratová hodnota

true, pokud je v rozsahu nalezen libovolný prvek, jinak false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) funkce


Kontroluje, zda měnitelný span obsahuje libovolný prvek v určeném rozsahu.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spasmu (musí být porovnatelné) |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Měnitelný span, ve kterém se hledá |
| lowInclusive | const T\& | Dolní mez (včetně) |
| highInclusive | const T\& | Horní mez (včetně) |

### Návratová hodnota

true, pokud je v rozsahu nalezen libovolný prvek, jinak false

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)