---
title: GetNameValueWithParametersLength()
second_title: Aspose.Slides for C++ API 參考
description: 將傳入的字串從指定索引轉換為 NameValueWithParametersHeaderValue 類別的實例。
type: docs
weight: 92
url: /zh-hant/system.net.http.headers/namevaluewithparametersheadervalue/getnamevaluewithparameterslength/
---
## NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String, int32_t, System::SharedPtr\<Object\>\&) 方法


將傳入的字串從指定索引轉換為 [NameValueWithParametersHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 用於解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 已解析物件將指派到的實例。 |

### 返回值

返回已解析子字串的長度，若無則返回 0。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [NameValueWithParametersHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 程式庫 [Aspose.Slides](../../../)