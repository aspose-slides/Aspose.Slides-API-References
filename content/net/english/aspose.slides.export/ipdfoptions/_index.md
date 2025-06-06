---
title: IPdfOptions
second_title: Aspose.Sildes for .NET API Reference
description: Provides options that control how a presentation is saved in Pdf format.
type: docs
weight: 3870
url: /aspose.slides.export/ipdfoptions/
---

## IPdfOptions interface

Provides options that control how a presentation is saved in Pdf format.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Contains a set of flags specifying which access permissions should be granted when the document is opened with user access. See [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. Read/write String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Applies the specified transparent color to an image if `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Returns ISaveOptions interface. Read-only [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Indicates if the most effective compression (instead of the default one) for each image must be selected automatically. If set to Boolean.true, for every image in presentation the most appropriate compression algorithm will be chosen, what will lead to the smaller size of the resulting PDF document. Best image compression ratio selection is computationally expensive and takes an additional amount of RAM, and this option is Boolean.false by default. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Desired conformance level for generated PDF document. Read/write [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True to draw black frame around each slide. Read/write Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Determines if all characters of font should be embedded or only used subset. Read/write Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True to embed true type fonts for ASCII characters 32-127. Fonts for character codes greater than 127 are always embedded. Read/write Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Gets or sets the image transparent color. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True to convert all OLE data from the presentation to embedded files in the resulting PDF. Read/write Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Provides options that control the look of Ink objects in exported document. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Returns or sets a value determining the quality of the JPEG images inside PDF document. Read/write Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Setting user password to protect the PDF document. Read/write String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indicates whether text should be rasterized as a bitmap and saved to PDF when the font does not support bold styling. This approach can enhance the quality of text in the resulting PDF for certain fonts. Read/write Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True to convert all metafiles used in a presentation to the PNG images. Read/write Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Returns or sets a value determining resolution of images inside PDF document. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Specifies compression type to be used for all textual content in the document. Read/write [`PdfTextCompression`](../pdftextcompression). |

### See Also

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
