---
title: Contains()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查唯讀 span 是否包含特定值。
type: docs
weight: 40
url: /zh-hant/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) 函式


檢查唯讀 span 是否包含特定值。

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | 要搜尋的 span |
| value | const T\& | 要搜尋的值 |

### 返回值

如果在 span 中找到 value，則回傳 true；否則回傳 false

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) 函式


檢查可變 span 是否包含特定值。

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | span 中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | 要搜尋的可變 span |
| value | const T\& | 要搜尋的值 |

### 返回值

如果在 span 中找到 value，則回傳 true；否則回傳 false

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函式


檢查字元 span 是否包含另一個字元 span，且使用特定的比較規則。

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜尋的 span |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要搜尋的 span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要執行的字串比較類型 |

### 返回值

如果在 span 中找到 value，則回傳 true；否則回傳 false

## 另請參見

* 列舉 [StringComparison](../../system/stringcomparison/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)