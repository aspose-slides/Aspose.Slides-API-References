---
title: CommonPrefixLength()
second_title: Aspose.Slides for C++ API Reference
description: Finds the length of the common prefix between two spans.
type: docs
weight: 27
url: /system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the length of the common prefix between two spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span |

### Return Value

The number of matching elements at the beginning of both spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function


Finds the length of the common prefix between a mutable span and a read-only span.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span |

### Return Value

The number of matching elements at the beginning of both spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) function


Finds the length of the common prefix between two mutable spans.

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The first mutable span |
| other | const [Span](../../system/span/)\<T\>\& | The second mutable span |

### Return Value

The number of matching elements at the beginning of both spans

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function


Finds the length of the common prefix between two spans using a custom equality comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |
| TEqualityComparer | The type of the equality comparer |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The first span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The second span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | The equality comparer to use for element comparison |

### Return Value

The number of matching elements at the beginning of both spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function


Finds the length of the common prefix between a mutable span and a read-only span using a custom equality comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |
| TEqualityComparer | The type of the equality comparer |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The mutable span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The read-only span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | The equality comparer to use for element comparison |

### Return Value

The number of matching elements at the beginning of both spans

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) function


Finds the length of the common prefix between two mutable spans using a custom equality comparer.

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |
| TEqualityComparer | The type of the equality comparer |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The first mutable span |
| other | const [Span](../../system/span/)\<T\>\& | The second mutable span |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | The equality comparer to use for element comparison |

### Return Value

The number of matching elements at the beginning of both spans

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)