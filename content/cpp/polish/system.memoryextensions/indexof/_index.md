---
title: IndexOf()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Znajduje indeks wartości ReadOnlySpan<T> w innym ReadOnlySpan<T>
type: docs
weight: 144
url: /pl/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Znajduje indeks wartości ReadOnlySpan<T> w innym ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy szukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, którego należy szukać |

### Wartość zwracana

Indeks zerowy pierwszego wystąpienia lub -1, jeśli nie znaleziono

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) funkcja


Znajduje indeks pojedynczej wartości w ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, w którym należy szukać |
| value | const T\& | Wartość, której należy szukać |

### Wartość zwracana

Indeks zerowy pierwszego wystąpienia lub -1, jeśli nie znaleziono

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkcja


Znajduje indeks wartości ReadOnlySpan<T> w Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresach |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Zakres, którego należy szukać |

### Wartość zwracana

Indeks zerowy pierwszego wystąpienia lub -1, jeśli nie znaleziono

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) funkcja


Znajduje indeks pojedynczej wartości w Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ elementów w zakresie |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Zakres, w którym należy szukać |
| value | const T\& | Wartość, której należy szukać |

### Wartość zwracana

Indeks zerowy pierwszego wystąpienia lub -1, jeśli nie znaleziono

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkcja


Znajduje indeks wartości ReadOnlySpan<char16_t> w ReadOnlySpan<char16_t> przy użyciu StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres, w którym należy szukać |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Wartość, której należy szukać |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porównania ciągów do użycia |

### Wartość zwracana

Indeks zerowy pierwszego wystąpienia lub -1, jeśli nie znaleziono

## Zobacz także

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)