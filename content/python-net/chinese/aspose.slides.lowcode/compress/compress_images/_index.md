---
title: compress_images method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
降低演示文稿中图片的分辨率并删除其裁剪区域，类似于 PowerPoint 对所有图片应用的 “Compress Pictures”。  
处理幻灯片、版式幻灯片和母版幻灯片上的图片，包括组形状内的图片以及形状的图片填充。

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) | 要处理的演示文稿。 |
| resolution | [`PicturesCompression`](/slides/python-net/zh/aspose.slides.export/picturescompression) | 相对于每张图片显示尺寸的目标分辨率。<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/zh/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) 保持图片不变。 |

### 备注

已达到或低于目标分辨率的图片保持不变；图片永不放大。

未处理的内容：幻灯片背景、表格单元格填充、图表、SmartArt、GIF 图像（保留动画）、SVG 和元文件（EMF/WMF）图像。

裁剪区域被永久删除，无法在 PowerPoint 中恢复。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` 为 `None`。 |

### 另见
* 类 [`Compress`](/slides/python-net/zh/aspose.slides.lowcode/compress)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 枚举 [`PicturesCompression`](/slides/python-net/zh/aspose.slides.export/picturescompression)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)