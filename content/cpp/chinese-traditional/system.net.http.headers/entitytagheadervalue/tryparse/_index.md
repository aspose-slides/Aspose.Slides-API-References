---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考文件
description: 嘗試將傳入的字串轉換為 EntityTagHeaderValue 類別的實例。
type: docs
weight: 105
url: /zh-hant/system.net.http.headers/entitytagheadervalue/tryparse/
---
## EntityTagHeaderValue::TryParse(String, System::SharedPtr\<EntityTagHeaderValue\>\&) 方法

嘗試將傳入的字串轉換為 [EntityTagHeaderValue](../) 類別的實例。

```cpp
static bool System::Net::Http::Headers::EntityTagHeaderValue::TryParse(String input, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 回傳值

解析成功時返回 True，否則返回 false。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [EntityTagHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 程式庫 [Aspose.Slides](../../../)