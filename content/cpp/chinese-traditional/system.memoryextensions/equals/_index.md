---
title: Equals()
second_title: Aspose.Slides C++ API 參考
description: 使用 StringComparison 比較兩個 ReadOnlySpan<char16_t> 是否相等。
type: docs
weight: 417
url: /zh-hant/system.memoryextensions/equals/
---
## System::MemoryExtensions::Equals(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函式

使用 StringComparison 比較兩個 ReadOnlySpan<char16_t> 的相等性。

```cpp
bool System::MemoryExtensions::Equals(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 第一個 span 用於比較 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 第二個 span 用於比較 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 使用的字串比較類型 |

### 傳回值

若這些 span 相等，則回傳 true；否則回傳 false

## 另請參閱

* 列舉 [StringComparison](../../system/stringcomparison/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)