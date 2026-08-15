---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 嘗試將傳入的字串轉換為 MediaTypeHeaderValue 類別的實例。
type: docs
weight: 131
url: /zh-hant/system.net.http.headers/mediatypeheadervalue/tryparse/
---
## MediaTypeHeaderValue::TryParse(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) 方法

嘗試將傳入的字串轉換為 [MediaTypeHeaderValue](../) 類別的例項。

```cpp
static bool System::Net::Http::Headers::MediaTypeHeaderValue::TryParse(String input, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | 已解析物件將被指派到的例項。 |

### 回傳值

當解析成功完成時返回 true，否則返回 false。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)