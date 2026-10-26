---
title: GetMediaTypeLength()
second_title: Aspose.Slides for C++ API 參考
description: 將傳入的字串從指定索引轉換為 MediaTypeHeaderValue 類別的實例。
type: docs
weight: 144
url: /zh-hant/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) 方法


將傳入的字串從指定索引轉換為 [MediaTypeHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | 用於建立 [MediaTypeHeaderValue](../) 類別實例的委派。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 傳回值

傳回已解析子字串的長度，否則傳回 0。

## 另見

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [MediaTypeHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 程式庫 [Aspose.Slides](../../../)