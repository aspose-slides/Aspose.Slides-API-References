---
title: SequenceCompareTo()
second_title: Aspose.Slides pro C++ API referenci
description: Porovnává dva ReadOnlySpans lexikograficky.
type: docs
weight: 313
url: /cs/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Porovná dva ReadOnlySpan lexikograficky.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | První span k porovnání |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Druhý span k porovnání |

### Návratová hodnota

- 1 pokud span < other, 0 pokud span == other, 1 pokud span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce


Porovná [Span](../../system/span/) a [ReadOnlySpan](../../system/readonlyspan/) lexikograficky.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) k porovnání |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) k porovnání |

### Návratová hodnota

- 1 pokud span < other, 0 pokud span == other, 1 pokud span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) funkce


Porovná [ReadOnlySpan](../../system/readonlyspan/) a [Span](../../system/span/) lexikograficky.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků ve spanech |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) k porovnání |
| other | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) k porovnání |

### Návratová hodnota

- 1 pokud span < other, 0 pokud span == other, 1 pokud span > other

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)