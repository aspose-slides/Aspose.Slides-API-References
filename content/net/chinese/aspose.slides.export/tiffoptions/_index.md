---
title: TiffOptions
second_title: Aspose.Slides for .NET API 参考
description: 提供控制演示文稿如何以 TIFF 格式保存的选项
type: docs
weight: 4140
url: /zh/aspose.slides.export/tiffoptions/
---
## TiffOptions class

提供控制演示文稿如何以 TIFF 格式保存的选项。

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TiffOptions](tiffoptions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | 指定压缩类型。 读/写[`TiffCompressionTypes`](../tiffcompressiontypes)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 返回或设置在未找到源字体时使用的字体。 读写String。 |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | 以每英寸点数指定水平分辨率。 读/写UInt32。 |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | 以每英寸点数指定垂直分辨率。 读/写UInt32。 |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | 指定生成的 TIFF 图像的大小。 默认值为0x0，表示生成的图像大小将根据演示幻灯片大小值计算。 读/写Size。 |
| [NotesCommentsLayouting](../../aspose.slides.export/tiffoptions/notescommentslayouting) { get; } | 提供控制注释和注释在导出文档中的放置方式的选项。 |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | 指定生成图像的像素格式。 读/写[`ImagePixelFormat`](../imagepixelformat)。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 表示用于保存进度更新百分比的回调对象。 见[`IProgressCallback`](../../aspose.slides/iprogresscallback)。 |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | 指定生成的文档是否应包含隐藏幻灯片。 默认为` false` 。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 返回一个对象，该对象接收警告并决定加载过程是继续还是中止。 读/写[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 也可以看看

* class [SaveOptions](../saveoptions)
* interface [ITiffOptions](../itiffoptions)
* 命名空间 [Aspose.Slides.Export](../../aspose.slides.export)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
