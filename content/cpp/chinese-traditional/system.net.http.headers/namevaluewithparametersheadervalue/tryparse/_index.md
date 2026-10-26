---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考手冊
description: 嘗試將傳入的字串轉換為 NameValueWithParametersHeaderValue 類別的實例。
type: docs
weight: 79
url: /zh-hant/system.net.http.headers/namevaluewithparametersheadervalue/tryparse/
---
## NameValueWithParametersHeaderValue::TryParse(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) 方法

嘗試將傳入的字串轉換為 [NameValueWithParametersHeaderValue](../) 類別的實例。

```cpp
static bool System::Net::Http::Headers::NameValueWithParametersHeaderValue::TryParse(String input, System::SharedPtr<NameValueWithParametersHeaderValue> &parsedValue)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 返回值

若成功完成解析則為 True，否則為 false。

## 另請參考

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [NameValueWithParametersHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 程式庫 [Aspose.Slides](../../../)