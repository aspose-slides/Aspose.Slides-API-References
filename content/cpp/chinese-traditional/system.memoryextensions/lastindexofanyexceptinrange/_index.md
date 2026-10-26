---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides for C++ API 參考
description: 在跨度中尋找指定範圍之外的最後一次出現的任何元素。
type: docs
weight: 248
url: /zh-hant/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函式


在跨度內搜尋指定範圍之外的最後一次出現的任何元素。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 返回值

範圍外最後一個元素的零基索引，若未找到則為 -1

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) 函式


在可變跨度內搜尋指定範圍之外的最後一次出現的任何元素。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | The type of elements in the span |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### 返回值

範圍外最後一個元素的零基索引，若未找到則為 -1

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)