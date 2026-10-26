---
title: StartsWith()
second_title: Aspose.Slides C++ API 参考
description: 检查 span 是否以指定的 value 开头。
type: docs
weight: 352
url: /zh/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) 函数

检查 span 是否以指定的 value 开头。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查的 span |
| value | const T\& | 在 span 开头要检查的 value |

### 返回值

如果 span 以 value 开头则返回 true，否则返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

检查 span 是否以指定的 value span 开头。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 在开头要检查的值所在的 span |

### 返回值

如果 span 以 value span 开头则返回 true，否则返回 false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

检查可变 span 是否以指定的只读 value span 开头。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要检查的可变 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要检查的值的只读 span |

### 返回值

如果 span 以 value span 开头则返回 true，否则返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 函数

检查只读 span 是否以指定的可变 value span 开头。

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查的只读 span |
| value | const [Span](../../system/span/)\<T\>\& | 包含要检查的值的可变 span |

### 返回值

如果 span 以 value span 开头则返回 true，否则返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函数

使用字符串比较检查字符 span 是否以指定的 value span 开头。

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要检查的字符 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 包含要检查的值的字符 span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要执行的字符串比较类型 |

### 返回值

如果 span 以 value span 开头则返回 true，否则返回 false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) 函数

检查字符串 span 是否以指定的字符数组开头。

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | 要检查的字符串 span |
| val | const char16_t * | 在开头要检查的字符数组 |

### 返回值

如果 span 以字符数组开头则返回 true，否则返回 false

## 另见

* 枚举 [StringComparison](../../system/stringcomparison/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 类 [String](../../system/string/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)