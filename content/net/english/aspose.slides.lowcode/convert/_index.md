---
title: Convert
second_title: Aspose.Sildes for .NET API Reference
description: Represents a group of methods intended to convert Presentation../aspose.slides/presentation.
type: docs
weight: 7710
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
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to PDF. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Converts [`Presentation`](../../aspose.slides/presentation) to SVG. |

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
