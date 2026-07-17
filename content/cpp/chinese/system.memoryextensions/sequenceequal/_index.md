---
title: SequenceEqual()
second_title: Aspose.Slides C++ API 参考
description: 确定两个 ReadOnlySpan 是否按相同顺序包含相同的元素。
type: docs
weight: 326
url: /zh/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

确定两个 ReadOnlySpan 是否按相同顺序包含相同的元素。

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的第一个跨度 |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的第二个跨度 |

### 返回值

如果跨度具有相同长度且所有元素相等则返回 true，否则返回 false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

确定 [Span](../../system/span/) 和 [ReadOnlySpan](../../system/readonlyspan/) 是否按相同顺序包含相同的元素。

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要比较的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的 [ReadOnlySpan](../../system/readonlyspan/) |

### 返回值

如果跨度具有相同长度且所有元素相等则返回 true，否则返回 false

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 函数

使用自定义比较器确定两个 ReadOnlySpan 是否包含相等的元素。

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |
| TComparer | 比较器对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的第一个跨度 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的第二个跨度 |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用于元素比较的比较器对象智能指针 |

### 返回值

如果跨度具有相同长度且比较器认为所有元素相等则返回 true，否则返回 false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) 函数

使用自定义比较器确定 [Span](../../system/span/) 和 [ReadOnlySpan](../../system/readonlyspan/) 是否包含相等的元素。

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |
| TComparer | 比较器对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要比较的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的 [ReadOnlySpan](../../system/readonlyspan/) |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | 用于元素比较的比较器对象智能指针 |

### 返回值

如果跨度具有相同长度且比较器认为所有元素相等则返回 true，否则返回 false

## 另请参见

* Typedef [SharedPtr](../../system/sharedptr/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)