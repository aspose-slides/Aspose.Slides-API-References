---
title: ToLower()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的文化將字元轉換為小寫。
type: docs
weight: 443
url: /zh-hant/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) 函式


使用指定的文化將字元轉換為小寫。

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 需要轉換的來源字元範圍 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 用於儲存轉換後字元的目的地範圍 |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | 用於轉換的文化（nullptr 代表使用當前文化） |

### 回傳值

已轉換的字元數量，若目的地太小則回傳 -1

## 另請參閱

* Typedef [SharedPtr](../../system/sharedptr/)
* 類別 [ReadOnlySpan](../../system/readonlyspan/)
* 類別 [Span](../../system/span/)
* 類別 [CultureInfo](../../system.globalization/cultureinfo/)
* 命名空間 [System::MemoryExtensions](../)
* 函式庫 [Aspose.Slides](../../)