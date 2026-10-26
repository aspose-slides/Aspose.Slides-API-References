---
title: best_images_compression_ratio property
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio 属性
指示是否应为每个图像选择最有效的压缩（而不是默认压缩），必须自动进行
            如果设置为 **bool**.true，则在演示文稿中的每个图像将选择最合适的压缩
            算法，这将导致生成的 PDF 文档体积更小。
            最佳图像压缩比的选择计算量大且会占用额外的 RAM，
            默认情况下此选项为 **bool**.false。

### 备注

默认是 **bool**.false。

### 定义：
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```

### 另见
* 类 [`IPdfOptions`](/slides/python-net/zh/aspose.slides.export/ipdfoptions)
* 模块 [`aspose.slides.export`](/slides/python-net/zh/aspose.slides.export)
* 库 [`Aspose.Slides`](/slides/python-net)