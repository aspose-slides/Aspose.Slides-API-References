---
title: EndsWith()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje, zda ReadOnlySpan<T> končí jedinou hodnotou.
type: docs
weight: 131
url: /cs/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) funkce


Určuje, zda ReadOnlySpan<T> končí jedinou hodnotou.

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se má zkontrolovat |
| value | const T\& | Hodnota, kterou zkontrolovat na konci spanu |

### Návratová hodnota

true, pokud span končí hodnotou, false jinak

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Určuje, zda ReadOnlySpan<T> končí jiným ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se má zkontrolovat |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se má zkontrolovat na konci cílového spanu |

### Návratová hodnota

true, pokud span končí hodnotovým spanu, false jinak

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Určuje, zda Span<T> končí ReadOnlySpan<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, který se má zkontrolovat |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se má zkontrolovat na konci cílového spanu |

### Návratová hodnota

true, pokud span končí hodnotovým spanu, false jinak

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funkce


Určuje, zda ReadOnlySpan<T> končí Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, který se má zkontrolovat |
| value | const [Span](../../system/span/)\<T\>\& | Span, který se má zkontrolovat na konci cílového spanu |

### Návratová hodnota

true, pokud span končí hodnotovým spanu, false jinak

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) funkce


Určuje, zda Span<T> končí jiným Span<T>

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span, který se má zkontrolovat |
| value | const [Span](../../system/span/)\<T\>\& | Span, který se má zkontrolovat na konci cílového spanu |

### Návratová hodnota

true, pokud span končí hodnotovým spanu, false jinak

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) funkce


Určuje, zda ReadOnlySpan<char16_t> končí zadanou hodnotou pomocí StringComparison.

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span, který se má zkontrolovat |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Hodnota, kterou zkontrolovat na konci spanu |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Typ porovnání řetězců, který se má použít |

### Návratová hodnota

true, pokud span končí hodnotou, false jinak

## Viz také

* Výčet [StringComparison](../../system/stringcomparison/)
* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)