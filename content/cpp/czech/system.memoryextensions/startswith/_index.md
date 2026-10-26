---
title: StartsWith()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Kontroluje, zda span začíná zadanou hodnotou.
type: docs
weight: 352
url: /cs/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) funkce

Kontroluje, zda span začíná zadanou hodnotou.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se má zkontrolovat |
| value | const T\& | Hodnota, která se má na začátku spanu zkontrolovat |

### Návratová hodnota

true, pokud span začíná hodnotou, jinak false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Kontroluje, zda span začíná zadaným spanem hodnoty.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se má zkontrolovat |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span obsahující hodnoty, které se mají na začátku zkontrolovat |

### Návratová hodnota

true, pokud span začíná hodnotou, jinak false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Kontroluje, zda měnitelný span začíná zadaným pouze pro čtení spanem hodnoty.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Měnitelný span, který se má zkontrolovat |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pouze pro čtení obsahující hodnoty, které se mají zkontrolovat |

### Návratová hodnota

true, pokud span začíná hodnotou, jinak false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funkce

Kontroluje, zda span pouze pro čtení začíná zadaným měnitelným spanem hodnoty.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span pouze pro čtení, který se má zkontrolovat |
| value | const [Span](../../system/span/)\<T\>\& | Měnitelný span obsahující hodnoty, které se mají zkontrolovat |

### Návratová hodnota

true, pokud span začíná hodnotou, jinak false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkce

Kontroluje, zda znakový span začíná zadaným spanem hodnoty pomocí porovnání řetězců.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový span, který se má zkontrolovat |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Znakový span obsahující hodnoty, které se mají zkontrolovat |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porovnání řetězců, které se má provést |

### Návratová hodnota

true, pokud span začíná hodnotou, jinak false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) funkce

Kontroluje, zda řetězcový span začíná zadaným polem znaků.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | Řetězcový span, který se má zkontrolovat |
| val | const char16_t * | Pole znaků, které se má na začátku zkontrolovat |

### Návratová hodnota

true, pokud span začíná polem znaků, jinak false

## Viz také

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [String](../../system/string/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)