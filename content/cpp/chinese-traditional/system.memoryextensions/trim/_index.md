---
title: Trim()
second_title: Aspose.Slides for C++ API 參考文件
description: 從有型 span 的兩端修剪指定的元素。
type: docs
weight: 365
url: /zh-hant/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) function

從有型 span 的兩端修剪指定的元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElement | T | The element to trim |

### 傳回值

一個新的 span，已從兩端修剪指定的元素

## System::MemoryExtensions::Trim(Span\<T\>\&, T) function

從可變的有型 span 的兩端修剪指定的元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElement | T | The element to trim |

### 傳回值

一個新的 span，已從兩端修剪指定的元素

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

從有型 span 的兩端修剪指定的元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### 傳回值

一個新的 span，已從兩端修剪指定的元素

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

從可變的有型 span 的兩端修剪指定的元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The mutable span to trim |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The elements to trim |

### 傳回值

一個新的 span，已從兩端修剪指定的元素

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) function

從字元 span 的兩端修剪空白字元。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The character span to trim |

### 傳回值

一個新的 span，已從兩端修剪空白字元

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) function

從可變的字元 span 的兩端修剪空白字元。

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | The mutable character span to trim |

### 傳回值

一個新的 span，已從兩端修剪空白字元

## 另見

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)