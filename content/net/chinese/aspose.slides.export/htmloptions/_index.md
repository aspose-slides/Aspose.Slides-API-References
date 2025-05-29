---
title: HtmlOptions
second_title: Aspose.Sildes for .NET API Reference
description: 表示HTML导出选项。
type: docs
weight: 3720
url: /zh/aspose.slides.export/htmloptions/
---

## HtmlOptions class

表示HTML导出选项。

```csharp
public class HtmlOptions : SaveOptions, IHtmlOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HtmlOptions](htmloptions#constructor)() | 创建一个新的HtmlOptions对象，用于保存为单个HTML文件。 |
| [HtmlOptions](htmloptions#constructor_1)(ILinkEmbedController) | 创建一个新的HtmlOptions对象，指定回调。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 返回或设置在找不到源字体的情况下使用的字体。可读写字符串。 |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/htmloptions/deletepicturescroppedareas) { get; set; } | 一个布尔标志，指示裁剪的部分是否作为文档的一部分保留。如果为true，则裁剪部分将被移除；如果为false，则它们将被序列化到文档中（这可能导致文件变大） |
| [DisableFontLigatures](../../aspose.slides.export/htmloptions/disablefontligatures) { get; set; } | 获取或设置一个值，指示文本是否在不使用连字的情况下呈现。当设置为`true`时，渲染输出中将禁用连字。默认情况下，此属性设置为`false`。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | 返回或设置渐变的视觉样式。可读写 [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [HtmlFormatter](../../aspose.slides.export/htmloptions/htmlformatter) { get; set; } | 返回或设置HTML模板。可读写 [`IHtmlFormatter`](../ihtmlformatter)。 |
| [InkOptions](../../aspose.slides.export/htmloptions/inkoptions) { get; } | 提供控制导出文档中Ink对象外观的选项。只读 [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/htmloptions/jpegquality) { get; set; } | 返回或设置一个值，确定PDF文档中JPEG图像的质量。可读写字节。 |
| [PicturesCompression](../../aspose.slides.export/htmloptions/picturescompression) { get; set; } | 表示图像压缩级别 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 表示用于保存进度更新的回调对象的百分比。请参见 [`IProgressCallback`](../../aspose.slides/iprogresscallback)。 |
| [ShowHiddenSlides](../../aspose.slides.export/htmloptions/showhiddenslides) { get; set; } | 指定生成的文档是否应包含隐藏幻灯片。默认值为`false`。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | 指定保存演示文稿时是否跳过包含JavaScript调用的超链接。可读写布尔值。默认值为**false**。 |
| [SlideImageFormat](../../aspose.slides.export/htmloptions/slideimageformat) { get; set; } | 返回或设置幻灯片图像格式选项。可读写 [`ISlideImageFormat`](../islideimageformat)。 |
| [SlidesLayoutOptions](../../aspose.slides.export/htmloptions/slideslayoutoptions) { get; set; } | 获取或设置导出演示文稿时幻灯片在页面上放置的模式 [`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [SvgResponsiveLayout](../../aspose.slides.export/htmloptions/svgresponsivelayout) { get; set; } | 如果为true，则从svg容器中排除宽度和高度属性 - 这将使布局响应式。为false则相反。可读写布尔值。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 返回或设置一个接收警告的对象，并决定加载过程是否继续或中止。可读写 [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 另请参阅

* class [SaveOptions](../saveoptions)
* interface [IHtmlOptions](../ihtmloptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)