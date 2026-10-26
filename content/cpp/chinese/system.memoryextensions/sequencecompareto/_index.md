---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API 参考
description: 按字典顺序比较两个 ReadOnlySpans。
type: docs
weight: 313
url: /zh/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

按字典顺序比较两个 ReadOnlySpans。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的第一个跨度 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的第二个跨度 |

### 返回值

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

按字典顺序比较 [Span](../../system/span/) 和 [ReadOnlySpan](../../system/readonlyspan/)。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
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

- 1 if span < other, 0 if span == other, 1 if span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 函数

按字典顺序比较 [ReadOnlySpan](../../system/readonlyspan/) 和 [Span](../../system/span/)。

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要比较的 [ReadOnlySpan](../../system/readonlyspan/) |
| other | const [Span](../../system/span/)\<T\>\& | 要比较的 [Span](../../system/span/) |

### 返回值

- 1 if span < other, 0 if span == other, 1 if span > other

## 另见

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)