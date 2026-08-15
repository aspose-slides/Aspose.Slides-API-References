---
title: ToUpper()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的文化將字元轉換為大寫。
type: docs
weight: 469
url: /zh-hant/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) 函式

將字元轉換為大寫，使用指定的文化。

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 要轉換的來源字元 span |
| destination | [Span](../../system/span/)\<char16_t\>\& | 用於儲存已轉換字元的目的地 span |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | 用於轉換的文化（nullptr 代表目前的文化） |

### 回傳值

已轉換的字元數，若目的地太小則回傳 -1

## 另見

* 型別定義 [SharedPtr](../../system/sharedptr/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 類別 [CultureInfo](../../system.globalization/cultureinfo/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)