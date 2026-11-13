---
title: PdfOptions
second_title: Aspose.Sildes .NET API 参考
description: 提供控制演示文稿以 Pdf 格式保存方式的选项。
type: docs
weight: 4350
url: /zh/aspose.slides.export/pdfoptions/
---
## PdfOptions 类

提供控制演示文稿以 Pdf 格式保存方式的选项。

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfOptions](pdfoptions)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | 包含一组标志，指定在使用用户访问打开文档时应授予的访问权限。参见 [`PdfAccessPermissions`](../pdfaccesspermissions)。 |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | 返回或设置 Aspose.Slides 应视为通用的用户自定义字体系列名称数组。读/写 String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | 如果为 `true`，则将指定的透明颜色应用于图像。 |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | 指示是否必须为每个图像自动选择最有效的压缩（而非默认压缩）。如果设置为 Boolean.true，则演示文稿中的每个图像都会选择最合适的压缩算法，从而导致生成的 PDF 文档体积更小。最佳图像压缩比的选择计算量大且会占用额外的内存，默认情况下此选项为 Boolean.false。 |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | 生成的 PDF 文档所需的符合级别。读/写 [`PdfCompliance`](../pdfcompliance)。 |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 返回或设置在未找到源字体时使用的字体。读/写 String。 |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | 设置为 true 可在每张幻灯片周围绘制黑色框。读/写 Boolean。 |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | 确定是嵌入字体的所有字符还是仅嵌入使用的子集。读/写 Boolean。 |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | 确定 Aspose.Slides 是否会为 ASCII（33..127 代码范围）文本嵌入常用字体。字符代码大于 127 的字体始终嵌入。常用字体列表包括 PDF 的基本 14 种字体以及其他用户指定的字体。读/写 Boolean。 |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | 返回或设置渐变的视觉样式。读/写 [`GradientStyle`](../../aspose.slides/gradientstyle)。 |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | 获取或设置图像的透明颜色。 |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | 设置为 true 可将演示文稿中的所有 OLE 数据转换为生成的 PDF 中的嵌入文件。读/写 Boolean。 |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | 提供控制导出文档中墨迹对象外观的选项。只读 [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | 返回或设置决定 PDF 文档中 JPEG 图像质量的值。读/写 Byte。 |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | 设置用于保护 PDF 文档的用户密码。读/写 String。 |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 表示用于以百分比形式保存进度更新的回调对象。参见 [`IProgressCallback`](../../aspose.slides/iprogresscallback)。 |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | 指示当字体不支持粗体样式时，文本是否应光栅化为位图并保存到 PDF。此方法可以提升某些字体在生成的 PDF 中的文本质量。读/写 Boolean。 |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | 设置为 true 可将演示文稿中使用的所有元文件转换为 PNG 图像。读/写 Boolean。 |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | 指定生成的文档是否应包含隐藏幻灯片。默认值为 `false`。 |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读/写 Boolean。默认值为 **false**。 |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 [`ISlidesLayoutOptions`](../islideslayoutoptions)。 |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | 返回或设置决定 PDF 文档中图像分辨率的值。 |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | 指定用于文档中所有文本内容的压缩类型。读/写 [`PdfTextCompression`](../pdftextcompression)。 |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 返回或设置接收警告并决定加载过程是继续还是中止的对象。读/写 [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |

### 示例

以下示例演示如何使用自定义选项将 PowerPoint 转换为 PDF。

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// 实例化 PdfOptions 类
	PdfOptions pdfOptions = new PdfOptions();
	// 设置 Jpeg 质量
	pdfOptions.JpegQuality = 90;
	// 设置元文件的行为
	pdfOptions.SaveMetafilesAsPng = true;
	// 设置文本压缩级别
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// 定义 PDF 标准
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// 将演示文稿保存为 PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下示例演示如何在包含隐藏幻灯片的情况下将 PowerPoint 转换为 PDF。

```csharp
[C#]
// 实例化一个表示 PowerPoint 文件的 Presentation 类
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// 实例化 PdfOptions 类
	PdfOptions pdfOptions = new PdfOptions();
	// 添加隐藏幻灯片
	pdfOptions.ShowHiddenSlides = true;
	// 将演示文稿保存为 PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下示例演示如何将 PowerPoint 转换为受密码保护的 PDF。

```csharp
[C#]
// 实例化一个表示 PowerPoint 文件的 Presentation 对象
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// 实例化 PdfOptions 类
	PdfOptions pdfOptions = new PdfOptions();
	// 设置 PDF 密码和访问权限
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// 将演示文稿保存为 PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

以下示例演示如何将 PowerPoint 转换为带备注的 PDF。

```csharp
[C#]
// 实例化一个表示演示文稿文件的 Presentation 对象
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// 设置幻灯片类型和大小
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### 参见

* 类 [SaveOptions](../saveoptions)
* 接口 [IPdfOptions](../ipdfoptions)
* 命名空间 [Aspose.Slides.Export](../../aspose.slides.export)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->