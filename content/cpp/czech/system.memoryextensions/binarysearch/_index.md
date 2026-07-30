---
title: BinarySearch()
second_title: Aspose.Slides pro C++ – reference API
description: Provádí binární vyhledávání v seřazeném spanu.
type: docs
weight: 14
url: /cs/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) funkce

Provádí binární vyhledávání v seřazeném spanu.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |
| TComparable | Typ porovnávané hodnoty |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Seřazený span pro hledání |
| comparable | const TComparable\& | Hodnota, kterou hledat |

### Návratová hodnota

[Index](../../system/index/) nalezeného prvku, nebo bitový doplněk místa vložení, pokud nebyl nalezen

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) funkce

Provádí binární vyhledávání v seřazeném spanu s vlastním komparátorem.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |
| TComparer | Typ komparátoru |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Seřazený span pro hledání |
| value | const T\& | Hodnota, kterou hledat |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Komparátor používaný pro porovnávání |

### Návratová hodnota

[Index](../../system/index/) nalezeného prvku, nebo bitový doplněk místa vložení, pokud nebyl nalezen

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) funkce

Provádí binární vyhledávání v měnitelném seřazeném spanu.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |
| TComparable | Typ porovnávané hodnoty |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Seřazený span pro hledání |
| comparable | const TComparable\& | Hodnota, kterou hledat |

### Návratová hodnota

[Index](../../system/index/) nalezeného prvku, nebo bitový doplněk místa vložení, pokud nebyl nalezen

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) funkce

Provádí binární vyhledávání v měnitelném seřazeném spanu s vlastním komparátorem.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |
| TComparer | Typ komparátoru |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Seřazený span pro hledání |
| value | const T\& | Hodnota, kterou hledat |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Komparátor používaný pro porovnávání |

### Návratová hodnota

[Index](../../system/index/) nalezeného prvku, nebo bitový doplněk místa vložení, pokud nebyl nalezen

## Viz také

* Definice typu [SharedPtr](../../system/sharedptr/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)