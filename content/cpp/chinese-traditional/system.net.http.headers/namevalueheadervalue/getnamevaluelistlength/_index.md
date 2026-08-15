---
title: GetNameValueListLength()
second_title: Aspose.Slides for C++ API 參考文件
description: 將傳入的字串從指定索引轉換為 NameValueHeaderValue 類別實例的集合，並返回已解析子字串的長度。
type: docs
weight: 131
url: /zh-hant/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) 方法

將傳入的字串從指定索引轉換為 NameValueHeaderValue 類別實例的集合，並返回已解析子字串的長度。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 用於分析的字串。 |
| startIndex | **int32_t** | 用於分析的起始位置。 |
| delimiter | char16_t | 用於分隔指定字串中項目的字串。 |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | 輸出參數，解析後的集合將被指派給此參數。 |

### 回傳值

已解析子字串的長度。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [ObjectCollection](../../objectcollection/)
* 類別 [NameValueHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)