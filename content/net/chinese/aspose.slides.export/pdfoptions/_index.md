---  
title: PdfOptions
second_title: Aspose.Sildes for .NET API Reference  
description: 提供控制演示文稿以Pdf格式保存的选项。
type: docs
weight: 4140  
url: /zh/aspose.slides.export/pdfoptions/
---  

## PdfOptions class  

提供控制演示文稿以Pdf格式保存的选项。  

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | 包含一组标志，指定打开文档时应授予哪些访问权限。参见 [`PdfAccessPermissions`](../pdfaccesspermissions)。 |  
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | 返回或设置Aspose.Slides应视为常见的用户定义字体系列名称数组。读/写 String[]。 |  
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | 如果为`true`，则将指定的透明颜色应用于图像。 |  
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | 指示是否必须自动选择每个图像的最有效压缩（而不是默认压缩）。如果设置为 Boolean.true，则演示文稿中的每个图像将选择最合适的压缩算法，这将导致生成的PDF文档的大小更小。最佳图像压缩比选择计算成本高，并需要额外的RAM，此选项默认值为 Boolean.false。 |  
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | 生成PDF文档所需的符合性级别。读/写 [`PdfCompliance`](../pdfcompliance)。 |  
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | 返回或设置当未找到源字体时使用的字体。读写 String。 |  
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | 如果为 true，则在每个幻灯片周围绘制黑色框架。读/写 Boolean。 |  
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | 确定是否应嵌入字体的所有字符或仅使用子集。读/写 Boolean。 |  
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | 确定Aspose.Slides是否将为ASCII（33..127代码范围）文本嵌入常见字体。大于127的字符编码的字体总是嵌入的。常见字体列表包括PDF的基本14种字体和其他用户指定的字体。读/写 Boolean。 |  
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | 返回或设置渐变的视觉样式。读/写 [`GradientStyle`](../../aspose.slides/gradientstyle)。 |  
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | 获取或设置图像的透明颜色。 |  
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | 如果为 true，则将演示文稿中的所有OLE数据转换为生成PDF中的嵌入文件。读/写 Boolean。 |  
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | 提供控制导出文档中Ink对象外观的选项。读/只读 [`IInkOptions`](../iinkoptions) |  
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | 返回或设置确定PDF文档内JPEG图像质量的值。读/写 Byte。 |  
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | 设置用户密码以保护PDF文档。读/写 String。 |  
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | 表示用于保存进度更新百分比的回调对象。参见 [`IProgressCallback`](../../aspose.slides/iprogresscallback)。 |  
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | 指示在字体不支持粗体样式时，文本是否应作为位图栅格化并保存到PDF中。这种方法可以提高某些字体在生成的PDF中的文本质量。读/写 Boolean。 |  
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | 如果为 true，则将演示文稿中使用的所有元文件转换为PNG图像。读/写 Boolean。 |  
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | 指定生成的文档是否应包含隐藏幻灯片。默认值为`false`。 |  
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | 指定在保存演示文稿时是否跳过带有JavaScript调用的超链接。读/写 Boolean。默认值为 **false**。 |  
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | 获取或设置导出演示文稿时幻灯片在页面上的放置模式[`ISlidesLayoutOptions`](../islideslayoutoptions)。 |  
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | 返回或设置确定PDF文档内图像分辨率的值。 |  
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | 指定要用于文档中所有文本内容的压缩类型。读/写 [`PdfTextCompression`](../pdftextcompression)。 |  
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | 返回或设置一个对象，该对象接收警告并决定加载过程是否继续或中止。读/写 [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback)。 |  

### 例子  

以下示例演示如何使用自定义选项将PowerPoint转换为PDF。  

```csharp  
[C#]  
using (Presentation presentation = new Presentation("PowerPoint.pptx"))  
{  
	// 实例化PdfOptions类  
	PdfOptions pdfOptions = new PdfOptions();  
	// 设置JPEG质量  
	pdfOptions.JpegQuality = 90;  
	// 设置元文件的行为  
	pdfOptions.SaveMetafilesAsPng = true;  
	// 设置文本压缩级别  
	pdfOptions.TextCompression = PdfTextCompression.Flate;  
	// 定义PDF标准  
	pdfOptions.Compliance = PdfCompliance.Pdf15;  
	// 保存演示文稿为PDF  
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);  
}  
```  

以下示例演示如何将PowerPoint转换为PDF，并包含隐藏幻灯片。  

```csharp  
[C#]  
// 实例化表示PowerPoint文件的Presentation类  
using (Presentation presentation = new Presentation("PowerPoint.pptx"))  
{  
	// 实例化PdfOptions类  
	PdfOptions pdfOptions = new PdfOptions();  
	// 添加隐藏幻灯片  
	pdfOptions.ShowHiddenSlides = true;  
	// 保存演示文稿为PDF  
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);  
}  
```  

以下示例演示如何将PowerPoint转换为带密码保护的PDF。  

```csharp  
[C#]  
// 实例化表示PowerPoint文件的Presentation对象  
using (Presentation presentation = new Presentation("PowerPoint.pptx"))  
{  
	// 实例化PdfOptions类  
	PdfOptions pdfOptions = new PdfOptions();  
	// 设置PDF密码和访问权限  
	pdfOptions.Password = "password";  
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;  
	// 保存演示文稿为PDF  
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);  
}  
```  

以下示例演示如何将PowerPoint转换为带注释的PDF。  

```csharp  
[C#]  
// 实例化表示演示文稿文件的Presentation对象  
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

### 另见  

* class [SaveOptions](../saveoptions)  
* interface [IPdfOptions](../ipdfoptions)  
* namespace [Aspose.Slides.Export](../../aspose.slides.export)  
* assembly [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  