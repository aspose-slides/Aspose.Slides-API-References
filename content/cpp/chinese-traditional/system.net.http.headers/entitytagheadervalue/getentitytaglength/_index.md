---
title: GetEntityTagLength()
second_title: Aspose.Slides for C++ API 參考
description: 將傳入的字串從指定索引轉換為 EntityTagHeaderValue 類別的實例。
type: docs
weight: 118
url: /zh-hant/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) 方法

將傳入的字串從指定索引轉換為 [EntityTagHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | 已解析物件將被指派的實例。 |

### 回傳值

已解析子字串的長度，否則為 0。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [EntityTagHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)