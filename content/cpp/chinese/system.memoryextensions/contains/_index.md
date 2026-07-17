---
title: Contains()
second_title: Aspose.Slides C++ API 参考
description: 检查只读 span 是否包含特定值。
type: docs
weight: 40
url: /zh/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) 函数


检查只读 Span 是否包含特定值。

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的 Span |
| value | const T\& | 要搜索的值 |

### 返回值

如果在 Span 中找到值则返回 true，false 否则

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) 函数


检查可变 Span 是否包含特定值。

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | Span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的可变 Span |
| value | const T\& | 要搜索的值 |

### 返回值

如果在 Span 中找到值则返回 true，false 否则

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函数


检查字符 Span 是否包含另一个字符 Span，使用指定的比较规则。

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜索的 Span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜索的 Span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要执行的字符串比较类型 |

### 返回值

如果在 Span 中找到值则返回 true，false 否则

## 另请参见

* 枚举 [StringComparison](../../system/stringcomparison/)
* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)