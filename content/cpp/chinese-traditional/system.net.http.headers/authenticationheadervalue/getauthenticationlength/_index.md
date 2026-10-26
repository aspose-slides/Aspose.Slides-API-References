---
title: GetAuthenticationLength()
second_title: Aspose.Slides for C++ API 參考
description: 剖析指定的字串，並傳回字串表示形式的最後索引。
type: docs
weight: 118
url: /zh-hant/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength(String, int32_t, System::SharedPtr\<Object\>\&) 方法

剖析指定的字串，並傳回字串表示形式的最後索引。

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 必須剖析的字串。 |
| startIndex | **int32_t** | 剖析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 將指派已剖析值的輸出參數。 |

### 傳回值

已剖析子字串的長度，否則為 0。

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [AuthenticationHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)