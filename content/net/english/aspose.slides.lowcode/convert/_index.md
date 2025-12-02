---
title: Convert
second_title: Aspose.Sildes for .NET API Reference
description: Represents a group of methods intended to convert Presentation../aspose.slides/presentation.
type: docs
weight: 7820
url: /aspose.slides.lowcode/convert/
---

## Convert class

Represents a group of methods intended to convert [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Methods

| Name | Description |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Converts [`Presentation`](../../aspose.slides/presentation) using the passed output path extension to determine the required export format. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Converts the input presentation to a set of TIFF format images. If the output file name is given as "myPath/myFilename.tiff", the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Converts the input presentation to TIFF format with custom options. If the output file name is given as "myPath/myFilename.tiff" and *multipage* is `false`, the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number. Otherwise, if *multipage* is `true`, the result will be a multi-page "myPath/myFilename.tiff" document. |

## Other Members

| Name | Description |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback that will be invoked for each [`Slide`](../../aspose.slides/slide), the output path expected to be returned. |

### Examples

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### See Also

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
