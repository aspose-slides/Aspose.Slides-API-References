---
title: BinarySearch()
second_title: Aspose.Slides for C++ API 参考
description: 对已排序的 span 执行二分搜索。
type: docs
weight: 14
url: /zh/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) 函数


对已排序的 span 执行二分搜索。

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |
| TComparable | 可比较值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的已排序 span |
| comparable | const TComparable\& | 要搜索的值 |

### 返回值

找到的元素的索引；如果未找到，则返回插入点的按位取反

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) 函数


使用自定义比较器对已排序的 span 执行二分搜索。

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |
| TComparer | 比较器的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的已排序 span |
| value | const T\& | 要搜索的值 |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用于比较的比较器 |

### 返回值

找到的元素的索引；如果未找到，则返回插入点的按位取反

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) 函数


对可变的已排序 span 执行二分搜索。

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |
| TComparable | 可比较值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的已排序 span |
| comparable | const TComparable\& | 要搜索的值 |

### 返回值

找到的元素的索引；如果未找到，则返回插入点的按位取反

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) 函数


使用自定义比较器对可变的已排序 span 执行二分搜索。

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |
| TComparer | 比较器的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的已排序 span |
| value | const T\& | 要搜索的值 |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用于比较的比较器 |

### 返回值

找到的元素的索引；如果未找到，则返回插入点的按位取反

## 另请参见

* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)