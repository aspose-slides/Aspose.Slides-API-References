---
title: GetViaLength()
second_title: Aspose.Slides for C++ API 參考文件
description: 將傳入的字串從指定索引轉換為 ViaHeaderValue 類別的實例。
type: docs
weight: 131
url: /zh-hant/system.net.http.headers/viaheadervalue/getvialength/
---
## ViaHeaderValue::GetViaLength(String, int32_t, System::SharedPtr\<Object\>\&) 方法

將傳入的字串從指定索引轉換為 [ViaHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::ViaHeaderValue::GetViaLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 將指派已解析物件的實例。 |

### 回傳值

傳回已解析子字串的長度，否則傳回 0。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [ViaHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)