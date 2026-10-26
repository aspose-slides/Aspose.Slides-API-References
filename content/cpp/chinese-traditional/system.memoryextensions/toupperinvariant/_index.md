---
title: ToUpperInvariant()
second_title: Aspose.Slides for C++ API 參考
description: 使用不變文化將字符轉換為大寫。
type: docs
weight: 482
url: /zh-hant/system.memoryextensions/toupperinvariant/
---
## System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 函式

將字符轉換為使用不變文化的大寫形式。

```cpp
int32_t System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要轉換的來源字符跨度 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 用來存放已轉換字符的目標跨度 |

### 返回值

已轉換的字符數量；若目標過小則返回 -1

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)