---
title: SequenceEqual()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om två ReadOnlySpans innehåller identiska element i samma ordning.
type: docs
weight: 326
url: /sv/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Bestämmer om två ReadOnlySpans innehåller identiska element i samma ordning.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the spans |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |

### Returvärde

true if spans have same length and all elements are equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) funktion


Bestämmer om en [Span](../../system/span/) och [ReadOnlySpan](../../system/readonlyspan/) innehåller identiska element i samma ordning.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the spans |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |

### Returvärde

true if spans have same length and all elements are equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) funktion


Bestämmer om två ReadOnlySpans innehåller lika element med en anpassad jämförare.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### Returvärde

true if spans have same length and comparer considers all elements equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) funktion


Bestämmer om en [Span](../../system/span/) och [ReadOnlySpan](../../system/readonlyspan/) innehåller lika element med en anpassad jämförare.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### Returvärde

true if spans have same length and comparer considers all elements equal, false otherwise

## Se också

* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)