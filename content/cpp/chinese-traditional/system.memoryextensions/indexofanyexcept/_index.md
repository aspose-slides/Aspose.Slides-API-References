---
title: IndexOfAnyExcept()
second_title: Aspose.Slides for C++ API 參考
description: 在 ReadOnlySpan<T> 中找出第一個不等於指定值的元素的索引
type: docs
weight: 170
url: /zh-hant/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) 函式

在 ReadOnlySpan<T> 中尋找第一個不等於指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value | const T\& | 要從搜索中排除的值 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式

在 ReadOnlySpan<T> 中尋找第一個不等於任意兩個指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要從搜索中排除的第一個值 |
| value1 | const T\& | 要從搜索中排除的第二個值 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) 函式

在 ReadOnlySpan<T> 中尋找第一個不等於任意三個指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要從搜索中排除的第一個值 |
| value1 | const T\& | 要從搜索中排除的第二個值 |
| value2 | const T\& | 要從搜索中排除的第三個值 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) 函式

在 Span<T> 中尋找第一個不等於指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value | const T\& | 要從搜索中排除的值 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) 函式

在 Span<T> 中尋找第一個不等於任意兩個指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要從搜索中排除的第一個值 |
| value1 | const T\& | 要從搜索中排除的第二個值 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) 函式

在 Span<T> 中尋找第一個不等於任意三個指定值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| value0 | const T\& | 要從搜索中排除的第一個值 |
| value1 | const T\& | 要從搜索中排除的第二個值 |
| value2 | const T\& | 要從搜索中排除的第三個值 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

在一個值跨度中尋找第一個不等於任意值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜索的跨度 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要從搜索中排除的值的跨度 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) 函式

在 Span<T> 中的值跨度中尋找第一個不等於任意值的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 跨度中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜索的跨度 |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 包含要從搜索中排除的值的跨度 |

### 返回值

第一個不匹配元素的零基索引，若未找到則返回 -1

## 參見

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)