---
title: IndexOf()
second_title: Aspose.Slides C++ API 参考
description: 在另一个 ReadOnlySpan<T> 中查找 ReadOnlySpan<T> 值的索引
type: docs
weight: 144
url: /zh/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

在另一个 ReadOnlySpan<T> 中查找 ReadOnlySpan<T> 值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | The type of elements in the spans |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |

### 返回值

第一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) 函数

在 ReadOnlySpan<T> 中查找单个值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | The type of elements in the span |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |
| value | const T\& | 要搜索的值 |

### 返回值

第一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

在 Span<T> 中查找 ReadOnlySpan<T> 值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | The type of elements in the spans |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 span |

### 返回值

第一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) 函数

在 Span<T> 中查找单个值的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | The type of elements in the span |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的 span |
| value | const T\& | 要搜索的值 |

### 返回值

第一次出现的零基索引，如果未找到则返回 -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函数

使用 StringComparison 在 ReadOnlySpan<char16_t> 中查找 ReadOnlySpan<char16_t> 值的索引

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜索的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜索的值 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要使用的字符串比较类型 |

### 返回值

第一次出现的零基索引，如果未找到则返回 -1

## 另请参见

* 枚举 [StringComparison](../../system/stringcomparison/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)