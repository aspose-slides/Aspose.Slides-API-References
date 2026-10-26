---
title: ILinkEmbedController class
second_title: Aspose.Slides 在 Python 中通过 .NET 的 API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController 类

回调接口 用于确定在保存期间对象应如何处理。

The ILinkEmbedController type 公开以下成员：

## 方法

| 方法 | 说明 |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/zh/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | 确定对象应存储的位置。<br/>            此方法对每个对象 ID 调用一次。<br/>            不能保证不会存在具有相同 data、semanticName 和 contentType 但 ID 不同的两个对象。 |
| [`get_url(self, id, referrer)`](/slides/python-net/zh/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | 返回指向外部对象的 URL。<br/>            如果 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 返回 [`LinkEmbedDecision.LINK`](/slides/python-net/zh/aspose.slides.export/linkembeddecision/LINK)，则始终调用此方法；如果 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 返回 [`LinkEmbedDecision.EMBED`](/slides/python-net/zh/aspose.slides.export/linkembeddecision/EMBED) 且嵌入不可能时，也可能调用此方法。<br/>            可以对同一对象 ID 多次调用。 |
| [`save_external(self, id, entity_data)`](/slides/python-net/zh/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | 保存外部对象。 |


### 另请参见
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)