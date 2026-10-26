---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API 參考
description: 在 span 中尋找任意三個指定值的最後一次出現。
type: docs
weight: 222
url: /zh-hant/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函式


在 span 中尋找三個指定值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |
| value2 | const T\& | 要搜尋的第三個值 |

### 傳回值

最後一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) 函式


在可變的 span 中尋找三個指定值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |
| value2 | const T\& | 要搜尋的第三個值 |

### 傳回值

最後一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式


在 span 中尋找兩個指定值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |

### 傳回值

最後一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) 函式


在可變的 span 中尋找兩個指定值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要搜尋的第一個值 |
| value1 | const T\& | 要搜尋的第二個值 |

### 傳回值

最後一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


在 span 中尋找序列中任意值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的值序列 |

### 傳回值

最後一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


在可變的 span 中尋找序列中任意值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的值序列 |

### 傳回值

最後一次出現的零基索引，若未找到則返回 -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) 函式


在可變的 span 中尋找可變序列中任意值的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| values | const [Span](../../system/span/)\<T\>\& | 要搜尋的值序列 |

### 傳回值

最後一次出現的零基索引，若未找到則返回 -1

## 另請參閱

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)