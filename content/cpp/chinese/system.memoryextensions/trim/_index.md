---
title: Trim()
second_title: Aspose.Slides for C++ API 参考
description: 从有类型的 span 两端修剪指定的元素。
type: docs
weight: 365
url: /zh/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) 函数


从有类型的 span 两端修剪指定的元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的 span |
| trimElement | T | 要修剪的元素 |

### 返回值

一个新的 span，已从两端修剪指定的元素

## System::MemoryExtensions::Trim(Span\<T\>\&, T) 函数


从可变有类型的 span 两端修剪指定的元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要修剪的可变 span |
| trimElement | T | 要修剪的元素 |

### 返回值

一个新的 span，已从两端修剪指定的元素

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


从有类型的 span 两端修剪指定的多个元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的元素集合 |

### 返回值

一个新的 span，已从两端修剪指定的元素

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函数


从可变有类型的 span 两端修剪指定的多个元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | span 中元素的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要修剪的可变 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的元素集合 |

### 返回值

一个新的 span，已从两端修剪指定的元素

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) 函数


从字符 span 两端修剪空白字符。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 span |

### 返回值

一个新的 span，已从两端修剪空白字符

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) 函数


从可变字符 span 两端修剪空白字符。

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可变字符 span |

### 返回值

一个新的 span，已从两端修剪空白字符

## 另请参见

* 类 [ReadOnlySpan](../../system/readonlyspan/)
* 类 [Span](../../system/span/)
* 命名空间 [System::MemoryExtensions](../)
* 库 [Aspose.Slides](../../)