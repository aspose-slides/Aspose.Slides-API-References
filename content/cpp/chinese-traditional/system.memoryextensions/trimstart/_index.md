---
title: TrimStart()
second_title: Aspose.Slides for C++ API 參考
description: 從有類型的 span 開頭修剪指定的元素。
type: docs
weight: 391
url: /zh-hant/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) function

從有類型的 span 開頭修剪指定的元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的 span |
| trimElement | const T\& | 要修剪的元素 |

### 返回值

一個從開頭已修剪指定元素的新 span

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) function

從可變類型的 span 開頭修剪指定的元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要修剪的可變 span |
| trimElement | const T\& | 要修剪的元素 |

### 返回值

一個從開頭已修剪指定元素的新 span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

從有類型的 span 開頭修剪指定的元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的元素 |

### 返回值

一個從開頭已修剪指定元素的新 span

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

從可變類型的 span 開頭修剪指定的元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | 要修剪的可變 span |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要修剪的元素 |

### 返回值

一個從開頭已修剪指定元素的新 span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) function

從字符 span 的開頭修剪空白字元。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 span |

### 返回值

一個從開頭已修剪空白字元的新 span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) function

從可變字符 span 的開頭修剪空白字元。

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可變字符 span |

### 返回值

一個從開頭已修剪空白字元的新 span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) function

從字符 span 的開頭修剪指定的字元。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 span |
| trimchar | char16_t | 要修剪的字元 |

### 返回值

一個從開頭已修剪指定字元的新 span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) function

從可變字符 span 的開頭修剪指定的字元。

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可變字符 span |
| trimchar | char16_t | 要修剪的字元 |

### 返回值

一個從開頭已修剪指定字元的新 span

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

從字符 span 的開頭修剪指定的字元。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字符 span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字元 |

### 返回值

一個從開頭已修剪指定字元的新 span

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

從可變字符 span 的開頭修剪指定的字元。

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可變字符 span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字元 |

### 返回值

一個從開頭已修剪指定字元的新 span

## 另請參閱

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)