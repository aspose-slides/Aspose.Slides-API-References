---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試將傳入的字串轉換為 CacheControlHeaderValue 類別的實例。
type: docs
weight: 443
url: /zh-hant/system.net.http.headers/cachecontrolheadervalue/tryparse/
---
## CacheControlHeaderValue::TryParse(String, System::SharedPtr\<CacheControlHeaderValue\>\&) 方法

嘗試將傳遞的字串轉換為 [CacheControlHeaderValue](../) 類別的實例。

```cpp
static bool System::Net::Http::Headers::CacheControlHeaderValue::TryParse(String input, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | 將指派已解析物件的實例。 |

### 返回值

當解析成功完成時返回 True，否則返回 false。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [CacheControlHeaderValue](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)