---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查唯讀 span 是否包含任何超出指定範圍的元素。
type: docs
weight: 79
url: /zh-hant/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

檢查唯讀 span 是否包含任何超出指定範圍的元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型（必須可比較） |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| lowInclusive | const T\& | 下界（含） |
| highInclusive | const T\& | 上界（含） |

### 返回值

如果找到範圍外的任何元素則返回 true，否則返回 false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

檢查可變 span 是否包含任何超出指定範圍的元素。

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型（必須可比較） |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的可變 span |
| lowInclusive | const T\& | 下界（含） |
| highInclusive | const T\& | 上界（含） |

### 返回值

如果找到範圍外的任何元素則返回 true，否則返回 false

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)