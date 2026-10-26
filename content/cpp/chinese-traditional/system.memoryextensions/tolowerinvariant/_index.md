---
title: ToLowerInvariant()
second_title: Aspose.Slides for C++ API 參考
description: 使用不變區域將字元轉換為小寫。
type: docs
weight: 456
url: /zh-hant/system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 函式

使用不變區域將字元轉換為小寫。

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要轉換的來源字元 span |
| destination | [Span](../../system/span/)\<char16_t\>\& | 用來存放已轉換字元的目的地 span |

### 回傳值

已轉換的字元數量，若目的地太小則為 -1

## 另請參閱

* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)