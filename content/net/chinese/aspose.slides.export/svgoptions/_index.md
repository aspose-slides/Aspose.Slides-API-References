---
title: SVGOptions
second_title: Aspose.Sildes for .NET API Reference
description: 表示SVG选项。
type: docs
weight: 4240
url: /zh/aspose.slides.export/svgoptions/
---

## SVGOptions class

表示SVG选项。

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | 初始化SVGOptions类的新实例。 |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | 初始化SVGOptions类的新实例，指定链接嵌入控制器对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | 返回默认设置。只读 [`SVGOptions`](../svgoptions)。 |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | 返回用于生成最简单和最小SVG文件的设置。只读 [`SVGOptions`](../svgoptions)。 |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | 返回用于生成最准确SVG文件的设置。只读 [`SVGOptions`](../svgoptions)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 返回或设置在找不到源字体时使用的字体。可读写字符串。 |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | 布尔标志，指示裁剪部分是否保留为文档的一部分。如果为 true，则裁剪部分将被移除；如果为 false，则它们将被序列化到文档中（这可能导致文件变大）。 |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | 确定SVG中是否禁用3D文本。可读写布尔值。 |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | 获取或设置一个值，指示文本是否在渲染时不使用连字。当设置为 `true` 时，渲染输出中将禁用连字。默认情况下，此属性设置为 `false`。 |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | 禁用FromCornerX和FromCenter渐变的拆分。可读写布尔值。 |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1缺乏为标记定义内边距的能力。Aspose.Slides SVG写入引擎对此问题有解决方法：它裁剪带箭头的线的末端，因此线不会与标记重叠。此选项关闭这种行为。可读写布尔值。 |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | 确定处理外部加载字体的方式。可读写 [`SvgExternalFontsHandling`](../svgexternalfontshandling)。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | 返回或设置渐变的视觉样式。可读写 [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | 提供控制导出文档中Ink对象外观的选项。只读 [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | 确定JPEG编码质量。可读写Int32。 |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | 返回或设置元文件光栅化的下限分辨率。可读写Int32。 |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | 表示图像压缩级别 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 表示用于保存进度更新的回调对象，单位为百分比。参见 [`IProgressCallback`](../../aspose.slides/iprogresscallback)。 |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | 返回和设置一个回调接口，允许用户控制形状转换。可读写 [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller)。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | 指定在保存演示文稿时是否跳过带有JavaScript调用的超链接。可读写布尔值。默认值为 **false**。 |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | 确定在渲染时是否执行指定的形状旋转。可读写布尔值。默认值为 true。 |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | 确定文本框是否将包括在渲染区域内。可读写布尔值。默认值为 false。 |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | 确定幻灯片上的文本是否将作为图形保存。可读写布尔值。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 返回或设置一个接收警告并决定加载过程是否继续或中止的对象。可读写 [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 另请参阅

* class [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->