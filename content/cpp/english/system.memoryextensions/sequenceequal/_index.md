---
title: SequenceEqual()
second_title: Aspose.Slides for C++ API Reference
description: Determines if two ReadOnlySpans contain identical elements in the same order.
type: docs
weight: 365
url: /system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determines if two ReadOnlySpans contain identical elements in the same order.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |

### Return Value

true if spans have same length and all elements are equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Determines if a [Span](../../system/span/) and [ReadOnlySpan](../../system/readonlyspan/) contain identical elements in the same order.

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |

### Return Value

true if spans have same length and all elements are equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function


Determines if two ReadOnlySpans contain equal elements using a custom comparer.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### Return Value

true if spans have same length and comparer considers all elements equal, false otherwise

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) function


Determines if a [Span](../../system/span/) and [ReadOnlySpan](../../system/readonlyspan/) contain equal elements using a custom comparer.

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |
| TComparer | The type of the comparer object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The [Span](../../system/span/) to compare |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The [ReadOnlySpan](../../system/readonlyspan/) to compare |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

### Return Value

true if spans have same length and comparer considers all elements equal, false otherwise

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)