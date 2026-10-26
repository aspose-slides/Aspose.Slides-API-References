---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考文件
description: 嘗試將傳入的字串轉換為 NameValueHeaderValue 類別的實例。
type: docs
weight: 105
url: /zh-hant/system.net.http.headers/namevalueheadervalue/tryparse/
---
## NameValueHeaderValue::TryParse(String, System::SharedPtr\<NameValueHeaderValue\>\&) 方法

嘗試將傳入的字串轉換為 [NameValueHeaderValue](../) 類別的實例。

```cpp
static bool System::Net::Http::Headers::NameValueHeaderValue::TryParse(String input, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | 解析後的物件將指派給的實例。 |

### 返回值

解析成功時返回 true，否則返回 false。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [NameValueHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)