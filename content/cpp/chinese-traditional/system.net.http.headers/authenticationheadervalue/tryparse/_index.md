---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試將傳入的字串轉換為 AuthenticationHeaderValue 類別的實例。
type: docs
weight: 105
url: /zh-hant/system.net.http.headers/authenticationheadervalue/tryparse/
---
## AuthenticationHeaderValue::TryParse(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) 方法


將傳入的字串轉換為 [AuthenticationHeaderValue](../) 類別的實例。

```cpp
static bool System::Net::Http::Headers::AuthenticationHeaderValue::TryParse(String input, System::SharedPtr<AuthenticationHeaderValue> &parsedValue)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[AuthenticationHeaderValue](../)\>\& | 解析後物件將被指派的實例。 |

### 返回值

解析成功時返回 true，否則返回 false。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [AuthenticationHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)