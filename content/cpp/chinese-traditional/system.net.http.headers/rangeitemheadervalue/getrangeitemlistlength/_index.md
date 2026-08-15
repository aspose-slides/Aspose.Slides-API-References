---
title: GetRangeItemListLength()
second_title: Aspose.Slides for C++ API 參考
description: 將傳入的字串從指定位置轉換為 RangeItemHeaderValue 類別實例的集合。
type: docs
weight: 79
url: /zh-hant/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) 方法

將傳入的字串從指定位置轉換為 RangeItemHeaderValue 類別 實例的集合。

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | 將指派已解析集合的實例。 |

### 返回值

已解析子字串的長度，若無則為 0。

## 另請參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [ICollection](../../../system.collections.generic/icollection/)
* 類別 [RangeItemHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)