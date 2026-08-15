---
title: GetUrl()
second_title: "Aspose.Slides for C++ API 參考文件"
description: "傳回指向外部物件的 URL。 如果 ILinkEmbedController::GetObjectStoringLocation 回傳 LinkEmbedDecision::Link，則此方法必定被呼叫；如果 ILinkEmbedController::GetObjectStoringLocation 回傳 LinkEmbedDecision::Embed，但嵌入不可能，則可能被呼叫。 可對相同的物件 ID 多次呼叫。"
type: docs
weight: 14
url: /zh-hant/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) 方法

傳回指向外部物件的 URL。 如果 [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) 回傳 [LinkEmbedDecision::Link](../../linkembeddecision/)，此方法必定被呼叫；如果 [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) 回傳 [LinkEmbedDecision::Embed](../../linkembeddecision/)，且嵌入不可能，則可能被呼叫。 可對相同的物件 ID 多次呼叫。

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| id | **int32_t** | 物件 ID。此 ID 在整個操作期間唯一。 |
| referrer | **int32_t** | 參考物件的 ID，若物件由根文件參照則為 0。可用於產生相對連結。 |

### 回傳值

外部物件的 URL，若應忽略此物件則為 null。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [ILinkEmbedController](../)
* 名稱空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)