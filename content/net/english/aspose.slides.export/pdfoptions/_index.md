---
title: PdfOptions
second_title: Aspose.Sildes for .NET API Reference
description: Provides options that control how a presentation is saved in Pdf format.
type: docs
weight: 4200
url: /aspose.slides.export/pdfoptions/
---

## PdfOptions class

Provides options that control how a presentation is saved in Pdf format.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Applies the specified transparent color to an image if `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to Boolean.true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is Boolean.false by default. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Desired conformance level for generated PDF document. Read/write [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returns or sets font used in case source font is not found. Read-write String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True to draw black frame around each slide. Read/write Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Determines if all characters of font should be embedded or only used subset. Read/write Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Determines if Aspose.Slides will embed common fonts for ASCII (33..127 code range) text. Fonts for character codes greater than 127 are always embedded. Common fonts list includes PDF's base 14 fonts and additional user specified fonts. Read/write Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returns or sets the visual style of the gradient. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Gets or sets the image transparent color. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read/write Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Provides options that control the look of Ink objects in exported document. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Setting user password to protect the PDF document. Read/write String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Represents a callback object for saving progress updates in percentage. See [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. This approach can enhance the quality of text in the resulting PDF for certain fonts. Read/write Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True to convert all metafiles used in a presentation to the PNG images. Read/write Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read/write Boolean. The default value is **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Returns or sets a value determining resolution of images inside PDF document. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Specifies compression type to be used for all textual content in the document. Read/write [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Examples

The following example shows how to convert PowerPoint to PDF with custom options.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instantiates the PdfOptions class
	PdfOptions pdfOptions = new PdfOptions();
	// Sets the Jpeg quality
	pdfOptions.JpegQuality = 90;
	// Sets the behavior for metafiles
	pdfOptions.SaveMetafilesAsPng = true;
	// Sets the text compression level
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Defines the PDF standard
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Saves the presentation as a PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to PDF with hidden slides.

```csharp
[C#]
// Instantiates a Presentation class that represents a PowerPoint file
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instantiates the PdfOptions class
	PdfOptions pdfOptions = new PdfOptions();
	// Adds hidden slides
	pdfOptions.ShowHiddenSlides = true;
	// Saves the presentation as a PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to password protected PDF.

```csharp
[C#]
// Instantiates a Presentation object that represents a PowerPoint file
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instantiates the PdfOptions class
	PdfOptions pdfOptions = new PdfOptions();
	// Sets PDF password and access permissions
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Saves the presentation as a PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to PDF with notes.

```csharp
[C#]
// Instantiate a Presentation object that represents a presentation file
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Setting Slide Type and Size
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### See Also

* class [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
