---
title: GetCacheControlLength()
second_title: Aspose.Slides C++ API 參考
description: 將傳入的字串從指定索引轉換為 CacheControlHeaderValue 類別的實例。
type: docs
weight: 456
url: /zh-hant/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) 方法

將從指定索引開始的傳入字串轉換為 [CacheControlHeaderValue](../) 類別的實例。

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 用於解析的字串。 |
| startIndex | **int32_t** | 用於解析的起始位置。 |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | 必須加入已解析物件的值。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 傳回值

已解析子字串的長度，若無則為 0。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [CacheControlHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)