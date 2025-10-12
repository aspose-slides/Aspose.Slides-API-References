---
title: BinarySearch()
second_title: Aspose.Slides for C++ API Reference
description: Performs binary search on a sorted span.
type: docs
weight: 14
url: /system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) function


Performs binary search on a sorted span.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Return Value

Index of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function


Performs binary search on a sorted span using a custom comparer.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Return Value

Index of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) function


Performs binary search on a mutable sorted span.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### Return Value

Index of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) function


Performs binary search on a mutable sorted span using a custom comparer.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### Return Value

Index of the found element, or bitwise complement of the insertion point if not found

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)