---
title: CompareTo()
second_title: Aspose.Slides for C++ API 參考
description: 比較兩個字元區段，使用指定的字串比較規則。
type: docs
weight: 404
url: /zh-hant/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 函式

比較兩個字元區段，使用指定的字串比較規則。

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 第一個字元區段 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 第二個字元區段 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 要執行的字串比較類型 |

### 回傳值

如果 span < other 為負值，等於時為零，若 span > other 為正值

## 另請參閱

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)