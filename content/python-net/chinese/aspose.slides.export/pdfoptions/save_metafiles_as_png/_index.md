---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png 属性
True 将所有演示文稿中使用的 metafile 转换为 PNG 图像。
Read/write **bool**.

### 备注

默认值为 **true** 。
Pdf 文档可以包含矢量图形和光栅图像。 
如果将 SaveMetafilesAsPng 设置为 true，则源 Metafile 图像将转换为 Png 格式并作为光栅图像保存到 Pdf 中。 
如果将 SaveMetafilesAsPng 设置为 false，则源 Metafile 将转换为 Pdf 矢量图形。 
每种方法都有其优势和劣势。 
例如，如果 Metafile 被转换为 PNG，则在后续文档缩放时可能会出现一定的质量损失。 
如果 Metafile 被转换为 Pdf 矢量图形，则在 Pdf 查看工具中可能出现性能问题。

### 定义：
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### 另请参见
* 类 [`PdfOptions`](/slides/python-net/zh/aspose.slides.export/pdfoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)