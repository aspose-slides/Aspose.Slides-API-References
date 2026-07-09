---
title: Convert
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en grupp av metoder avsedda att konvertera Presentation../aspose.slides/presentation.
type: docs
weight: 7880
url: /sv/aspose.slides.lowcode/convert/
---
## Convert klass

Representerar en grupp av metoder avsedda att konvertera [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Konverterar [`Presentation`](../../aspose.slides/presentation) med hjälp av den angivna utdatafilens tillägg för att bestämma det erforderliga exportformatet. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Konverterar den inmatade presentationen till en uppsättning JPEG-formatbilder. Om utdatafilnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är ett bildnummer. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Konverterar den inmatade presentationen till en uppsättning JPEG-formatbilder. Om utdatafilnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är ett bildnummer. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Konverterar den inmatade presentationen till en uppsättning JPEG-formatbilder. Om utdatafilnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är ett bildnummer. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Konverterar [`Presentation`](../../aspose.slides/presentation) till PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Konverterar [`Presentation`](../../aspose.slides/presentation) till PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Konverterar [`Presentation`](../../aspose.slides/presentation) till PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Konverterar [`Presentation`](../../aspose.slides/presentation) till PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Konverterar den inmatade presentationen till en uppsättning PNG-formatbilder. Om utdatafilnamnet anges som "myPath/myFilename.png" sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är ett bildnummer. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Konverterar den inmatade presentationen till en uppsättning PNG-formatbilder. Om utdatafilnamnet anges som "myPath/myFilename.png" sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är ett bildnummer. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Konverterar den inmatade presentationen till en uppsättning PNG-formatbilder. Om utdatafilnamnet anges som "myPath/myFilename.png" sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är ett bildnummer. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Konverterar [`Presentation`](../../aspose.slides/presentation) till SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Konverterar [`Presentation`](../../aspose.slides/presentation) till SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Konverterar [`Presentation`](../../aspose.slides/presentation) till SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Konverterar [`Presentation`](../../aspose.slides/presentation) till SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Konverterar [`Presentation`](../../aspose.slides/presentation) till SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Konverterar den inmatade presentationen till en uppsättning TIFF-formatbilder. Om utdatafilnamnet anges som "myPath/myFilename.tiff" sparas resultatet som en uppsättning filer "myPath/myFilename_N.tiff", där N är ett bildnummer. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Konverterar den inmatade presentationen till TIFF-format med anpassade alternativ. Om utdatafilnamnet anges som "myPath/myFilename.tiff" och *multipage* är `false` sparas resultatet som en uppsättning filer "myPath/myFilename_N.tiff", där N är ett bildnummer. Annars, om *multipage* är `true`, blir resultatet ett flersidigt "myPath/myFilename.tiff"-dokument. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Återanrop som kommer att anropas för varje [`Slide`](../../aspose.slides/slide), den förväntade utdatasökvägen ska returneras. |

### Exempel

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Se även

* namnrymd [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->