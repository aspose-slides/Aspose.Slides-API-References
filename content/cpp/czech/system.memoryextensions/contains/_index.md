---
title: Contains()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda ReadOnlySpan obsahuje konkrétní hodnotu.
type: docs
weight: 40
url: /cs/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) funkce

Kontroluje, zda read-only span obsahuje konkrétní hodnotu.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, ve kterém se hledá |
| value | const T\& | Hodnota, kterou hledáte |

### Návratová hodnota

true, pokud je hodnota nalezena v span, false jinak

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) funkce

Kontroluje, zda mutable span obsahuje konkrétní hodnotu.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Mutable span, ve kterém se hledá |
| value | const T\& | Hodnota, kterou hledáte |

### Návratová hodnota

true, pokud je hodnota nalezena v span, false jinak

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkce

Kontroluje, zda znakový span obsahuje jiný znakový span s určenými pravidly porovnání.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Rozsah, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span, který se hledá |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ řetězcového porovnání, který se má provést |

### Návratová hodnota

true, pokud je hodnota nalezena v span, false jinak

## Viz také

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)