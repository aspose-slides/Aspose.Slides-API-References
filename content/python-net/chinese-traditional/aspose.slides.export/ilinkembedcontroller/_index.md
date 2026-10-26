---
title: ILinkEmbedController class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController 類別

回調介面，用於確定在儲存過程中應如何處理物件。

ILinkEmbedController 類型公開以下成員：

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/zh-hant/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | 確定物件應儲存的位置。<br/>            此方法對每個物件 id 只呼叫一次。<br/>            無法保證不會出現資料、semanticName 與 contentType 相同但 id 不同的兩個物件。 |
| [`get_url(self, id, referrer)`](/slides/python-net/zh-hant/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | 傳回外部物件的 URL。<br/>            當 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 回傳 [`LinkEmbedDecision.LINK`](/slides/python-net/zh-hant/aspose.slides.export/linkembeddecision/LINK) 時，必定會呼叫此方法；若 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 回傳 [`LinkEmbedDecision.EMBED`](/slides/python-net/zh-hant/aspose.slides.export/linkembeddecision/EMBED)，且無法嵌入，則可能會呼叫此方法。<br/>            此方法可能會對相同的物件 id 呼叫多次。 |
| [`save_external(self, id, entity_data)`](/slides/python-net/zh-hant/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | 儲存外部物件。 |


### 另見
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)