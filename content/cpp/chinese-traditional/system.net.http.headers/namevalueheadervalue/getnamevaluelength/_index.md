---
title: GetNameValueLength()
second_title: Aspose.Slides for C++ API 參考
description: 將傳入的字串從指定索引轉換為 NameValueHeaderValue 類別的實例。
type: docs
weight: 118
url: /zh-hant/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) 方法

將傳入的字串從指定索引轉換為 [NameValueHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 返回值

返回已解析子字串的長度，否則返回 0。

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) 方法

將傳入的字串從指定索引轉換為 [NameValueHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | 用於建立 [NameValueHeaderValue](../) 類別新實例的函式。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 返回值

返回已解析子字串的長度，否則返回 0。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [HeaderFunc](../../headerfunc/)
* 類別 [String](../../../system/string/)
* 類別 [NameValueHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)