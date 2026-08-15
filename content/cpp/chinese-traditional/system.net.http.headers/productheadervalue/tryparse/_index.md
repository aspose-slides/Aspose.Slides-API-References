---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試將傳入的字串轉換為 ProductHeaderValue 類別的實例。
type: docs
weight: 92
url: /zh-hant/system.net.http.headers/productheadervalue/tryparse/
---
## ProductHeaderValue::TryParse(String, System::SharedPtr\<ProductHeaderValue\>\&) 方法

嘗試將傳入的字串轉換為 [ProductHeaderValue](../) 類別的實例。

```cpp
static bool System::Net::Http::Headers::ProductHeaderValue::TryParse(String input, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | 會指派已解析物件的實例。 |

### 返回值

解析成功時返回 true，否則返回 false。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [ProductHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 程式庫 [Aspose.Slides](../../../)