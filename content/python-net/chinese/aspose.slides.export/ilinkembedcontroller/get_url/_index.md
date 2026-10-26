---
title: get_url method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Returns an URL to an external object.
            如果 **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** 返回 [`LinkEmbedDecision.LINK`](/slides/python-net/zh/aspose.slides.export/linkembeddecision/LINK)，则始终调用此方法；如果返回 [`LinkEmbedDecision.EMBED`](/slides/python-net/zh/aspose.slides.export/linkembeddecision/EMBED)，则可能调用此方法，但嵌入是不可能的。
            可以多次调用同一对象 id。

### 返回

外部对象的 URL，或者如果应忽略此对象则为 None。

```python
def get_url(self, id, referrer):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| id | **int** | 对象 id。此 id 在整个保存操作中唯一。 |
| referrer | **int** | 引用对象的 id，或者如果对象被根文档引用则为 0。可用于生成相对链接。 |

### 另见
* 类 [`ILinkEmbedController`](/slides/python-net/zh/aspose.slides.export/ilinkembedcontroller)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)