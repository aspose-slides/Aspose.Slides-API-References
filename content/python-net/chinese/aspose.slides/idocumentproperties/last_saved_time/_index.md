---
title: last_saved_time property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time 属性
返回演示文稿上次修改的日期。
            值采用 UTC。
            在 Presentation.DocumentProperties 中为只读（因为在 IPresentation 对象保存过程中会在内部更新）。
            可通过方法 [`IPresentationInfo.read_document_properties`](/slides/python-net/zh/aspose.slides/ipresentationinfo/read_document_properties) 返回的 DocumentProperties 实例进行更改。
            请参阅 **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** 方法摘要中的示例。

### 定义：
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```


### 参见
* 类 [`IDocumentProperties`](/slides/python-net/zh/aspose.slides/idocumentproperties)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)