---
title: SequenceEqual()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda dva ReadOnlySpans obsahují identické prvky ve stejném pořadí.
type: docs
weight: 326
url: /cs/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Určuje, zda dva ReadOnlySpans obsahují identické prvky ve stejném pořadí.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | The type of elements in the spans |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |

### Návratová hodnota

true pokud mají span stejnou délku a všechny prvky jsou stejné, false jinak

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funkce

Určuje, zda [Span](../../system/span/) a [ReadOnlySpan](../../system/readonlyspan/) obsahují identické prvky ve stejném pořadí.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | The type of elements in the spans |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) k porovnání |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) k porovnání |

### Návratová hodnota

true pokud mají span stejnou délku a všechny prvky jsou stejné, false jinak

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) funkce

Určuje, zda dva ReadOnlySpans obsahují stejné prvky pomocí vlastního komparátoru.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | První span k porovnání |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Druhý span k porovnání |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ukazatel chytrý na objekt komparátoru pro porovnání prvků |

### Návratová hodnota

true pokud mají span stejnou délku a komparátor považuje všechny prvky za stejné, false jinak

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) funkce

Určuje, zda [Span](../../system/span/) a [ReadOnlySpan](../../system/readonlyspan/) obsahují stejné prvky pomocí vlastního komparátoru.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) k porovnání |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) k porovnání |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Ukazatel chytrý na objekt komparátoru pro porovnání prvků |

### Návratová hodnota

true pokud mají span stejnou délku a komparátor považuje všechny prvky za stejné, false jinak

## Viz také

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)