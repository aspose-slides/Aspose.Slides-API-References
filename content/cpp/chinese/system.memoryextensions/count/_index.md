---
title: Count()
second_title: Aspose.Slides for C++ API 参考
description: 统计只读跨度中某个值的出现次数。
type: docs
weight: 118
url: /zh/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) 函数

计算只读跨度中某个值的出现次数。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value | const T\& | 要计数的值 |

### 返回值

value 在 span 中出现的次数

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

计算只读跨度中另一个跨度的出现次数。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要计数出现次数的跨度 |

### 返回值

value 在 span 中出现的次数

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) 函数

计算 Span<T> 中单个值的出现次数。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value | const T\& | 要计数出现次数的值 |

### 返回值

value 在 span 中出现的次数

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

计算 Span<T> 中 ReadOnlySpan<T> 的出现次数。

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要计数出现次数的值的跨度 |

### 返回值

value span 在目标 span 中出现的次数

## 另见

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)