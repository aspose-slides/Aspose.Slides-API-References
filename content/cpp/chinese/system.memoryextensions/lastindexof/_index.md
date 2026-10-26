---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 参考
description: 在跨度中查找序列的最后一次出现。
type: docs
weight: 209
url: /zh/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

在跨度中查找序列的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要在其中搜索的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的序列 |

### 返回值

最后一次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) 函数

在跨度中查找单个值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要在其中搜索的跨度 |
| value | const T\& | 要搜索的值 |

### 返回值

最后一次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

在可变跨度中查找序列的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要在其中搜索的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的序列 |

### 返回值

最后一次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) 函数

在可变跨度中查找单个值的最后一次出现。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 跨度中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要在其中搜索的跨度 |
| value | const T\& | 要搜索的值 |

### 返回值

最后一次出现的零基索引，如果未找到则为 -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函数

使用指定的字符串比较在跨度中查找值的最后一次出现。

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要在其中搜索的跨度 |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜索的值 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要执行的字符串比较类型 |

### 返回值

最后一次出现的零基索引，如果未找到则为 -1

## 另见

* 枚举 [StringComparison](../../system/stringcomparison/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)