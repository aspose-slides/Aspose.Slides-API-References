---
title: TiffOptions
second_title: Aspose.Sildes for .NET API Reference
description: Provides options that control how a presentation is saved in TIFF format.
type: docs
weight: 4420
url: /aspose.slides.export/tiffoptions/
---

## TiffOptions class

Provides options that control how a presentation is saved in TIFF format.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Specifies the algorithm for converting a color image into a black and white image. This option will applied only if [`CompressionType`](./compressiontype) is set to CCITT4 or CCITT3 Read/write [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Default is Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Specifies the compression type. Read/write [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returns or sets font used in case source font is not found. Read-write String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Specifies the horizontal resolution in dots per inch. Read/write UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Specifies the vertical resolution in dots per inch. Read/write UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returns or sets the visual style of the gradient. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Specifies size of a generated TIFF image. Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value. Read/write Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Provides options that control the look of Ink objects in exported document. Read-only [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Specifies the pixel format for the generated images. Read/write [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Represents a callback object for saving progress updates in percentage. See [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Specifies whether the generated document should include hidden slides or not. Default is `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read/write Boolean. The default value is **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Gets or sets the mode in which slides are placed on the page when exporting a presentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Examples

The following example shows how to convert PowerPoint to TIFF with default size.

```csharp
[C#]
// Instantiate a Presentation object that represents a presentation file
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Saving the presentation to TIFF document
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

The following example shows how to convert PowerPoint to TIFF with custom size.

```csharp
[C#]
// Instantiate a Presentation object that represents a Presentation file
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instantiate the TiffOptions class
    TiffOptions opts = new TiffOptions();
    // Setting compression type
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Compression Types
    // Default - Specifies the default compression scheme (LZW).
    // None - Specifies no compression.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Depth depends on the compression type and cannot be set manually.
    // Resolution unit  is always equal to “2” (dots per inch)
    // Setting image DPI
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Set Image Size
    opts.ImageSize = new Size(1728, 1078);
    // Save the presentation to TIFF with specified image size
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

The following example shows how to convert PowerPoint to TIFF with custom image pixel format.

```csharp
[C#]
// Instantiate a Presentation object that represents a Presentation file
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat contains the following values (as could be seen from documentation):
    Format1bppIndexed; // 1 bits per pixel, indexed.
    Format4bppIndexed; // 4 bits per pixel, indexed.
    Format8bppIndexed; // 8 bits per pixel, indexed.
    Format24bppRgb; // 24 bits per pixel, RGB.
    Format32bppArgb; // 32 bits per pixel, ARGB.
    */
    // Save the presentation to TIFF with specified image size
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### See Also

* class [SaveOptions](../saveoptions)
* interface [ITiffOptions](../itiffoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
