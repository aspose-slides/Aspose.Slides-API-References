---
title: Sort()
second_title: Aspose.Slides for C++ API Reference
description: Sorts a Span using a custom comparer.
type: docs
weight: 378
url: /system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) function


Sorts a [Span](../../system/span/) using a custom comparer.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to sort |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for element comparison |

## System::MemoryExtensions::Sort(Span\<T\>\&) function


Sorts a [Span](../../system/span/) using default comparison.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The span to sort |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) function


Sorts key-value pairs using a custom comparer (keys and values sorted together)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |
| TComparer | The type of the comparer object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort (maintaining correspondence with keys) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer to comparer object for key comparison |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) function


Sorts key-value pairs using a comparison delegate.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegate for key comparison |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) function


Sorts key-value pairs using default comparison.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TKey | The type of keys |
| TValue | The type of values |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | The span of keys to sort |
| values | [Span](../../system/span/)\<TValue\>\& | The span of values to sort |

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Span](../../system/span/)
* Class [Comparison](../../system/comparison/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)