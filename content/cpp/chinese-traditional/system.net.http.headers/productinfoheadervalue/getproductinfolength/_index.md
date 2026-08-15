---
title: GetProductInfoLength()
second_title: Aspose.Slides C++ API 參考
description: 將傳入的字串從指定索引轉換為 ProductInfoHeaderValue 類別的實例。
type: docs
weight: 105
url: /zh-hant/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) 方法

將傳入的字串從指定索引轉換為 [ProductInfoHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 傳回值

傳回已解析子字串的長度，若無則傳回 0。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ProductInfoHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)