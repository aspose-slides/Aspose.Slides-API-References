---
title: BinarySearch()
second_title: Aspose.Slides for C++ API 參考
description: 在已排序的 span 上執行二分搜尋。
type: docs
weight: 14
url: /zh-hant/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) 函式

在已排序的 span 上執行二分搜尋。

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### 返回值

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) 函式

在已排序的 span 上使用自訂比較器執行二分搜尋。

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### 返回值

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) 函式

在可變的已排序 span 上執行二分搜尋。

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### 返回值

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) 函式

在可變的已排序 span 上使用自訂比較器執行二分搜尋。

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### 返回值

[Index](../../system/index/) of the found element, or bitwise complement of the insertion point if not found

## 另請參閱

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)