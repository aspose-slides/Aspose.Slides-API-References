---
title: TrimEnd()
second_title: Aspose.Slides for C++ API 参考
description: 从已键入的 span 末尾修剪指定元素。
type: docs
weight: 378
url: /zh/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) 函数

从已键入的 span 末尾修剪指定元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的 span |
| trimElement | const T\& | 要修剪的元素 |

### 返回值

一个新的 span，其末尾已修剪指定元素

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) 函数

从可变的已键入 span 末尾修剪指定元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要修剪的可变 span |
| trimElement | const T\& | 要修剪的元素 |

### 返回值

一个新的 span，其末尾已修剪指定元素

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

从已键入的 span 末尾修剪指定的元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的元素 |

### 返回值

一个新的 span，其末尾已修剪指定的元素

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数

从可变的已键入 span 末尾修剪指定的元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要修剪的可变 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的元素 |

### 返回值

一个新的 span，其末尾已修剪指定的元素

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) 函数

从字符 span 末尾修剪空白字符。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 span |

### 返回值

一个新的 span，其末尾已修剪空白字符

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) 函数

从可变的字符 span 末尾修剪空白字符。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可变字符 span |

### 返回值

一个新的 span，其末尾已修剪空白字符

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) 函数

从字符 span 末尾修剪指定字符。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 span |
| trimchar | char16_t | 要修剪的字符 |

### 返回值

一个新的 span，其末尾已修剪指定字符

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) 函数

从可变的字符 span 末尾修剪指定字符。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可变字符 span |
| trimchar | char16_t | 要修剪的字符 |

### 返回值

一个新的 span，其末尾已修剪指定字符

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 函数

从字符 span 末尾修剪指定字符。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 span |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 |

### 返回值

一个新的 span，其末尾已修剪指定字符

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 函数

从可变的字符 span 末尾修剪指定字符。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可变字符 span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 |

### 返回值

一个新的 span，其末尾已修剪指定字符

## 另见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)