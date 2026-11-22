---
title: Compress class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/compress/
---
## Compress 类

表示用于压缩 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation) 的一组方法。

Compress 类型公开以下成员：

## 方法

| 方法 | 描述 |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/zh/aspose.slides.lowcode/compress/compress_presentation/#presentation) | 通过应用所有可用的压缩步骤来减小演示文稿的大小：<br/>            * 移除未使用的母版幻灯片 **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**。<br/>* 移除未使用的布局幻灯片 **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**。<br/>* 仅保留嵌入字体中实际使用的字形 **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**。<br/>* 将图片分辨率降低到 150 DPI 并删除图片的裁剪区域 **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**。 |
| [`remove_unused_master_slides(pres)`](/slides/python-net/zh/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | 通过移除未使用的母版幻灯片来压缩 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)。 |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/zh/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | 通过移除未使用的布局幻灯片来压缩 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)。 |
| [`compress_embedded_fonts(pres)`](/slides/python-net/zh/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | 通过从嵌入字体中移除未使用的字符来压缩 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)。 |
| [`compress_images(presentation, resolution)`](/slides/python-net/zh/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | 降低演示文稿中图片的分辨率并删除它们的裁剪区域，<br/>            类似于对所有图片应用 PowerPoint 的 “Compress Pictures”。<br/>            对幻灯片、布局幻灯片和母版幻灯片上的图片进行处理，包括组形状内部的图片以及形状的图片填充。 |


### 另请参阅
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)