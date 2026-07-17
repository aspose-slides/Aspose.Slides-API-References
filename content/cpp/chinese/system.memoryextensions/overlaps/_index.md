---
title: Overlaps()
second_title: Aspose.Slides for C++ API 参考
description: 确定两个 ReadOnlySpans 在内存中是否重叠，而不计算偏移量。
type: docs
weight: 274
url: /zh/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

确定两个 ReadOnlySpans 在内存中是否重叠，而不计算偏移量。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查是否重叠的第一个跨度 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查是否重叠的第二个跨度 |

### 返回值

如果跨度共享任何公共内存位置则为 true，否则为 false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

确定 [Span](../../system/span/) 和 [ReadOnlySpan](../../system/readonlyspan/) 在内存中是否重叠，而不计算偏移量。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要检查是否重叠的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查是否重叠的 [ReadOnlySpan](../../system/readonlyspan/) |

### 返回值

如果跨度共享任何公共内存位置则为 true，否则为 false

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 函数

确定两个 ReadOnlySpans 在内存中是否重叠并计算偏移量。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查是否重叠的第一个跨度 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查是否重叠的第二个跨度 |
| elementOffset | **int32_t**\& | 如果跨度重叠，则接收跨度之间偏移量的输出参数 |

### 返回值

如果跨度共享任何公共内存位置则为 true，否则为 false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) 函数

确定 [Span](../../system/span/) 和 [ReadOnlySpan](../../system/readonlyspan/) 在内存中是否重叠并计算偏移量。

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要检查是否重叠的 [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查是否重叠的 [ReadOnlySpan](../../system/readonlyspan/) |
| elementOffset | **int32_t**\& | 如果跨度重叠，则接收跨度之间偏移量的输出参数 |

### 返回值

如果跨度共享任何公共内存位置则为 true，否则为 false

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)