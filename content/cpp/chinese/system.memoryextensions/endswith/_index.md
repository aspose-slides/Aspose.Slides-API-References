---
title: EndsWith()
second_title: Aspose.Slides for C++ API 参考
description: 确定 ReadOnlySpan<T> 是否以单个值结尾。
type: docs
weight: 131
url: /zh/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) 函数


确定 ReadOnlySpan<T> 是否以单个值结尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查的 span |
| value | const T\& | 要在 span 末尾检查的值 |

### 返回值

true if the span ends with the value, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


确定 ReadOnlySpan<T> 是否以另一个 ReadOnlySpan<T> 结尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要在目标 span 末尾检查的 span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


确定 Span<T> 是否以 ReadOnlySpan<T> 结尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要检查的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要在目标 span 末尾检查的 span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) 函数


确定 ReadOnlySpan<T> 是否以 Span<T> 结尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要检查的 span |
| value | const [Span](../../system/span/)\<T\>\& | 要在目标 span 末尾检查的 span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) 函数


确定 Span<T> 是否以另一个 Span<T> 结尾。

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | spans 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要检查的 span |
| value | const [Span](../../system/span/)\<T\>\& | 要在目标 span 末尾检查的 span |

### 返回值

true if the span ends with the value span, false otherwise

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函数


确定 ReadOnlySpan<char16_t> 是否使用 StringComparison 以指定的值结尾。

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要检查的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要在 span 末尾检查的值 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要使用的字符串比较类型 |

### 返回值

true if the span ends with the value, false otherwise

## 另请参见

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)