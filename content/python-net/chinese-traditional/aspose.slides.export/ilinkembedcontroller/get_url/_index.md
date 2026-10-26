---
title: get_url method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
傳回外部物件的 URL。
            此方法會在 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 回傳 [`LinkEmbedDecision.LINK`](/slides/python-net/zh-hant/aspose.slides.export/linkembeddecision/LINK) 時始終被呼叫，且在 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 回傳 [`LinkEmbedDecision.EMBED`](/slides/python-net/zh-hant/aspose.slides.export/linkembeddecision/EMBED) 時可能被呼叫，但無法嵌入。
            同一物件 id 可多次呼叫。

### 傳回

外部物件的 URL，若此物件應被忽略則為 None。



```python
def get_url(self, id, referrer):
    ...
```


| 參數 | 型別 | 說明 |
| :- | :- | :- |
| id | **int** | 物件 id。此 id 在整個操作中唯一。 |
| referrer | **int** | 參考物件的 id，若物件由根文件參考則為 0。可用於產生相對連結。 |



### 參見
* 類別 [`ILinkEmbedController`](/slides/python-net/zh-hant/aspose.slides.export/ilinkembedcontroller)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)