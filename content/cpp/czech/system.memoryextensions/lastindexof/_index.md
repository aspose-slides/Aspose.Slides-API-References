---
title: LastIndexOf()
second_title: Aspose.Slides pro C++ API Reference
description: Najde poslední výskyt sekvence ve spanu.
type: docs
weight: 209
url: /cs/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Najde poslední výskyt sekvence ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvence, která se má hledat |

### Návratová hodnota

Nulově indexovaný index posledního výskytu nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) funkce

Najde poslední výskyt jediné hodnoty ve spanu.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value | const T\& | Hodnota, která se má hledat |

### Návratová hodnota

Nulově indexovaný index posledního výskytu nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Najde poslední výskyt sekvence v měnitelné oblasti.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Sekvence, která se má hledat |

### Návratová hodnota

Nulově indexovaný index posledního výskytu nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) funkce

Najde poslední výskyt jediné hodnoty v měnitelné oblasti.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ elementů ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value | const T\& | Hodnota, která se má hledat |

### Návratová hodnota

Nulově indexovaný index posledního výskytu nebo -1, pokud nebyl nalezen

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkce

Najde poslední výskyt hodnoty ve spanu pomocí určeného řetězcového porovnání.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Hodnota, která se má hledat |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ řetězcového porovnání, které se má provést |

### Návratová hodnota

Nulově indexovaný index posledního výskytu nebo -1, pokud nebyl nalezen

## Viz také

* Výčet [StringComparison](../../system/stringcomparison/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)