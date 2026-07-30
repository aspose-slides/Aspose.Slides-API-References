---
title: IndexOf()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vyhledá index hodnoty ReadOnlySpan<T> v jiné ReadOnlySpan<T>
type: docs
weight: 144
url: /cs/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Vyhledá index hodnoty ReadOnlySpan<T> v jiné ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se hledá |

### Návratová hodnota

Nulová indexace první výskytu, nebo -1 pokud nebyla nalezena

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) function


Vyhledá index jediné hodnoty v ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, ve kterém se hledá |
| value | const T\& | Hodnota, která se hledá |

### Návratová hodnota

Nulová indexace první výskytu, nebo -1 pokud nebyla nalezena

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Vyhledá index hodnoty ReadOnlySpan<T> v Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se hledá |

### Návratová hodnota

Nulová indexace první výskytu, nebo -1 pokud nebyla nalezena

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) function


Vyhledá index jediné hodnoty v Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve span |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, ve kterém se hledá |
| value | const T\& | Hodnota, která se hledá |

### Návratová hodnota

Nulová indexace první výskytu, nebo -1 pokud nebyla nalezena

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function


Vyhledá index hodnoty ReadOnlySpan<char16_t> v ReadOnlySpan<char16_t> s použitím StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Hodnota, která se hledá |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porovnání řetězce, který se použije |

### Návratová hodnota

Nulová indexace první výskytu, nebo -1 pokud nebyla nalezena

## Viz také

* Výčet [StringComparison](../../system/stringcomparison/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)