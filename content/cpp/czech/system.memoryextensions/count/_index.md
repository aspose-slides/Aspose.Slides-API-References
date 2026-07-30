---
title: Count()
second_title: Aspose.Slides pro C++ API Reference
description: Počítá výskyty hodnoty v read-only rozsahu.
type: docs
weight: 118
url: /cs/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) function


Počítá výskyty hodnoty v read-only rozsahu.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, ve kterém se hledá |
| value | const T\& | Hodnota, kterou se má počítat |

### Návratová hodnota

Počet výskytů hodnoty v rozsahu

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Počítá výskyty rozsahu v jiném read-only rozsahu.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsazích |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah, jehož výskyty se mají počítat |

### Návratová hodnota

Počet výskytů hodnoty v rozsahu

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) function


Počítá výskyty jediné hodnoty v Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsahu |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rozsah, ve kterém se hledá |
| value | const T\& | Hodnota, jejíž výskyty se mají počítat |

### Návratová hodnota

Počet výskytů hodnoty v rozsahu

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Počítá výskyty ReadOnlySpan<T> v Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ prvků v rozsazích |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Rozsah, ve kterém se hledá |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Rozsah obsahující hodnoty, jejichž výskyty se mají počítat |

### Návratová hodnota

Počet výskytů rozsahu hodnot v cílovém rozsahu

## Viz také

* Třída [ReadOnlySpan](../../system/readonlyspan/)
* Třída [Span](../../system/span/)
* Jmenný prostor [System::MemoryExtensions](../)
* Knihovna [Aspose.Slides](../../)