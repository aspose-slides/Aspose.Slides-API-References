---
title: GetRangeConditionLength()
second_title: Aspose.Slides for C++ API 參考
description: 將傳入的字串從指定索引轉換為 RangeConditionHeaderValue 類別的實例。
type: docs
weight: 105
url: /zh-hant/system.net.http.headers/rangeconditionheadervalue/getrangeconditionlength/
---
## RangeConditionHeaderValue::GetRangeConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) 方法

將傳入的字串從指定索引轉換為 [RangeConditionHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::RangeConditionHeaderValue::GetRangeConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 已剖析物件將被指派的實例。 |

### 返回值

返回已剖析子字串的長度，否則返回 0。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [RangeConditionHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)