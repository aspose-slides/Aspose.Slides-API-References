---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides for C++ API 參考
description: 在 span 中尋找除三個指定值之外的任何元素的最後一次出現。
type: docs
weight: 235
url: /zh-hant/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函式


在 span 中尋找除三個指定值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要排除的第一個值 |
| value1 | const T\& | 要排除的第二個值 |
| value2 | const T\& | 要排除的第三個值 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 函式


在可變的 span 中尋找除三個指定值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要排除的第一個值 |
| value1 | const T\& | 要排除的第二個值 |
| value2 | const T\& | 要排除的第三個值 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式


在 span 中尋找除兩個指定值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要排除的第一個值 |
| value1 | const T\& | 要排除的第二個值 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) 函式


在可變的 span 中尋找除兩個指定值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value0 | const T\& | 要排除的第一個值 |
| value1 | const T\& | 要排除的第二個值 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 函式


在 span 中尋找除指定值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value | const T\& | 要排除的值 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) 函式


在可變的 span 中尋找除指定值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| value | const T\& | 要排除的值 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


在 span 中尋找除來自序列的值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要排除的值序列 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式


在可變的 span 中尋找除來自序列的值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要排除的值序列 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) 函式


在可變的 span 中尋找除來自可變序列的值之外的任何元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 span |
| values | const [Span](../../system/span/)\<T\>\& | 要排除的值序列 |

### 傳回值

最後一個未被排除元素的零基索引，若未找到則為 -1

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)