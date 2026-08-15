---
title: GetRangeItemLength()
second_title: Aspose.Slides for C++ API 參考
description: 將傳入的字串從指定的索引轉換為 RangeItemHeaderValue 類別的實例。
type: docs
weight: 92
url: /zh-hant/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) 方法

將傳入的字串從指定的索引轉換為 [RangeItemHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 回傳值

傳回已解析子字串的長度，若無則傳回 0。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [RangeItemHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)