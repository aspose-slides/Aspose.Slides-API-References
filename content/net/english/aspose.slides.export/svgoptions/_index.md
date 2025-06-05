---
title: SVGOptions
second_title: Aspose.Sildes for .NET API Reference
description: Represents an SVG options.
type: docs
weight: 4240
url: /aspose.slides.export/svgoptions/
---

## SVGOptions class

Represents an SVG options.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initializes a new instance of the SVGOptions class. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## Properties

| Name | Description |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Returns default settings. Read-only [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Returns settings for simpliest and smallest SVG file generation. Read-only [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Returns settings for most accurate SVG file generation. Read-only [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Returns or sets font used in case source font is not found. Read-write String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | A boolean flag indicates if the cropped parts remain as part of the document. If true the cropped parts will removed, if false they will be serialized in the document (which can possible lead to a larger file) |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Determines whether the 3D text is disabled in SVG. Read/write Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Gets or sets a value indicating whether text is rendered without using ligatures. When set to `true`, ligatures will be disabled in the rendered output. By default, this property is set to `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Disables splitting FromCornerX and FromCenter gradients. Read/write Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 lacks ability to define insets for markers. Aspose.Slides SVG writing engine has workaround for that problem: it crops end of line with arrow, so, line doesn't overlap markers. This option switches off such behavior. Read/write Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Determines a way of handling externally loaded fonts. Read/write [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Returns or sets the visual style of the gradient. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Provides options that control the look of Ink objects in exported document. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Determines JPEG encoding quality. Read/write Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Returns or sets the lower resolution limit for metafile rasterization. Read/write Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Represents the pictures compression level |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Represents a callback object for saving progress updates in percentage. See [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Returns and sets a callback interface which allows user to control shape conversion. Read/write [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Read/write Boolean. The default value is **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Determines whether to perform the specified rotation of the shape when rendering or not. Read/write Boolean. Default value is true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Determines whether the text frame will be included in a rendering area or not. Read/write Boolean. Default value is false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Determines whether the text on a slide will be saved as graphics. Read/write Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### See Also

* class [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
