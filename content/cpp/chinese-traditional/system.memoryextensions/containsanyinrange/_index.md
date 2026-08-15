---
title: ContainsAnyInRange()
second_title: Aspose.Slides for C++ API 參考
description: 檢查只讀 span 是否包含位於指定範圍內的任何元素。
type: docs
weight: 92
url: /zh-hant/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) 函數

檢查只讀 span 是否包含位於指定範圍內的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型（必須可比較） |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| lowInclusive | const T\& | 下界（包含） |
| highInclusive | const T\& | 上界（包含） |

### 傳回值

true if any element within the range is found, false otherwise

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) 函數

檢查可變 span 是否包含位於指定範圍內的任何元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型（必須可比較） |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的可變 span |
| lowInclusive | const T\& | 下界（包含） |
| highInclusive | const T\& | 上界（包含） |

### 傳回值

true if any element within the range is found, false otherwise

## 相關參考

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)