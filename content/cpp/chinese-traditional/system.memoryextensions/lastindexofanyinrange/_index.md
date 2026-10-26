---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides for C++ API 參考
description: 在 Span 中尋找指定範圍內任意元素的最後一次出現。
type: docs
weight: 261
url: /zh-hant/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

在只讀 Span 中尋找指定範圍內任意元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 Span |
| lowInclusive | const T\& | 範圍的下界（含） |
| highInclusive | const T\& | 範圍的上界（含） |

### 返回值

範圍內最後一個元素的零基索引，若未找到則返回 -1

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

在可變 Span 中尋找指定範圍內任意元素的最後一次出現。

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | Span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的 Span |
| lowInclusive | const T\& | 範圍的下界（含） |
| highInclusive | const T\& | 範圍的上界（含） |

### 返回值

範圍內最後一個元素的零基索引，若未找到則返回 -1

## 參見

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 名稱空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)