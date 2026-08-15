---
title: IndexOfAnyInRange()
second_title: Aspose.Slides for C++ API 參考文件
description: 在 ReadOnlySpan<T> 中尋找第一個位於指定範圍內的元素的索引
type: docs
weight: 196
url: /zh-hant/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式


在 ReadOnlySpan<T> 中尋找第一個位於指定範圍內的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的跨度 |
| lowInclusive | const T\& | 範圍的下界（含） |
| highInclusive | const T\& | 範圍的上界（含） |

### 傳回值

範圍內第一個元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) 函式


在 Span<T> 中尋找第一個位於指定範圍內的元素的索引

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的型別 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的跨度 |
| lowInclusive | const T\& | 範圍的下界（含） |
| highInclusive | const T\& | 範圍的上界（含） |

### 傳回值

範圍內第一個元素的零基索引，若未找到則為 -1

## 另見

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)