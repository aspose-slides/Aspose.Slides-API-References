---
title: TrimEnd()
second_title: Aspose.Slides for C++ API 參考
description: 從具型別的 span 結尾修剪指定的元素。
type: docs
weight: 378
url: /zh-hant/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) 函式


從具型別的 span 結尾修剪指定的元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
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

在結尾已修剪指定元素的新 span

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) 函式


從具可變型別的 span 結尾修剪指定的元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
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

在結尾已修剪指定元素的新 span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


從具型別的 span 結尾修剪指定的多個元素。

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
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

在結尾已修剪指定元素的新 span

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


從具可變型別的 span 結尾修剪指定的多個元素。

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
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

在結尾已修剪指定元素的新 span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) 函式


從字符 span 結尾修剪空白字元。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的 char16_t span |

### 返回值

在結尾已修剪空白字元的新 span

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) 函式


從可變字符 span 結尾修剪空白字元。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可變 char16_t span |

### 返回值

在結尾已修剪空白字元的新 span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) 函式


從字符 span 結尾修剪指定的字元。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的 char16_t span |
| trimchar | char16_t | 要修剪的字元 |

### 返回值

在結尾已修剪指定字元的新 span

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) 函式


從可變字符 span 結尾修剪指定的字元。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可變 char16_t span |
| trimchar | char16_t | 要修剪的字元 |

### 返回值

在結尾已修剪指定字元的新 span

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 函式


從字符 span 結尾修剪指定的多個字元。

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的 char16_t span |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字元 |

### 返回值

在結尾已修剪指定字元的新 span

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) 函式


從可變字符 span 結尾修剪指定的多個字元。

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | 要修剪的可變 char16_t span |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要修剪的字元 |

### 返回值

在結尾已修剪指定字元的新 span

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)