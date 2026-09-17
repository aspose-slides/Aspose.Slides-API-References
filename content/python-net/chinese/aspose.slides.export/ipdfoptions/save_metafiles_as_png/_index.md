---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png 属性
True 用于将演示文稿中使用的所有元文件转换为 PNG 图像.
            读/写 **bool**.

### 备注

默认是 **true** .
            Pdf 文档可以包含矢量图形和光栅图像. 
            如果 SaveMetafilesAsPng 设置为 true，则源 Metafile 图像将转换为 Png 格式并保存为 Pdf 的光栅图像. 如果 SaveMetafilesAsPng 设置为 false，则源 Metafile 将转换为 Pdf 矢量图形. 每种方法都有优点和缺点. 例如，如果 Metafile 被转换为 PNG，则在后续文档缩放时可能会出现一定的质量损失. 如果 Metafile 被转换为 Pdf 矢量图形，则可能出现 Pdf 查看工具的性能问题.

### 定义:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### 另见
* 类 [`IPdfOptions`](/slides/python-net/zh/aspose.slides.export/ipdfoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)