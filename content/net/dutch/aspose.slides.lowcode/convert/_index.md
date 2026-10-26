---
title: Convert
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om Presentation../aspose.slides/presentation te converteren.
type: docs
weight: 7880
url: /nl/aspose.slides.lowcode/convert/
---
## Convert klasse

Stelt een groep methoden voor die bedoeld zijn om [`Presentation`](../../aspose.slides/presentation) te converteren.

```csharp
public static class Convert
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Converteert [`Presentation`](../../aspose.slides/presentation) met behulp van de meegegeven output-pad-extensie om het vereiste exportformaat te bepalen. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Converteert de invoerpresentatie naar een reeks JPEG-formaat afbeeldingen. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.jpeg", waarbij N een slide-nummer is. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Converteert de invoerpresentatie naar een reeks JPEG-formaat afbeeldingen. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.jpeg", waarbij N een slide-nummer is. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Converteert de invoerpresentatie naar een reeks JPEG-formaat afbeeldingen. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.jpeg", waarbij N een slide-nummer is. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Converteert [`Presentation`](../../aspose.slides/presentation) naar PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Converteert [`Presentation`](../../aspose.slides/presentation) naar PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Converteert [`Presentation`](../../aspose.slides/presentation) naar PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Converteert [`Presentation`](../../aspose.slides/presentation) naar PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Converteert de invoerpresentatie naar een reeks PNG-formaat afbeeldingen. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een slide-nummer is. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Converteert de invoerpresentatie naar een reeks PNG-formaat afbeeldingen. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een slide-nummer is. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Converteert de invoerpresentatie naar een reeks PNG-formaat afbeeldingen. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.png", waarbij N een slide-nummer is. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Converteert [`Presentation`](../../aspose.slides/presentation) naar SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Converteert [`Presentation`](../../aspose.slides/presentation) naar SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Converteert [`Presentation`](../../aspose.slides/presentation) naar SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Converteert [`Presentation`](../../aspose.slides/presentation) naar SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Converteert [`Presentation`](../../aspose.slides/presentation) naar SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Converteert de invoerpresentatie naar een reeks TIFF-formaat afbeeldingen. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.tiff", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.tiff", waarbij N een slide-nummer is. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Converteert de invoerpresentatie naar TIFF-formaat met aangepaste opties. Als de outputbestandsnaam wordt opgegeven als "myPath/myFilename.tiff" en *multipage* `false` is, wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename_N.tiff", waarbij N een slide-nummer is. Anders, als *multipage* `true` is, wordt het resultaat een meer-pagina "myPath/myFilename.tiff" document. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback die wordt aangeroepen voor elke [`Slide`](../../aspose.slides/slide), waarbij het outputpad moet worden geretourneerd. |

### Voorbeelden

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Zie ook

* naamruimte [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->