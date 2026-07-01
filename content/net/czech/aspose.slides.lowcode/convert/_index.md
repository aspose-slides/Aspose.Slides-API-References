---
title: Convert
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje skupinu metod určených k převodu Presentation../aspose.slides/presentation.
type: docs
weight: 7860
url: /cs/aspose.slides.lowcode/convert/
---
## Convert třída

Reprezentuje skupinu metod určených k převodu [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Metody

| Název | Popis |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Převádí [`Presentation`](../../aspose.slides/presentation) pomocí předané přípony výstupní cesty k určení požadovaného exportního formátu. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je název výstupního souboru zadán jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je název výstupního souboru zadán jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je název výstupního souboru zadán jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Převádí [`Presentation`](../../aspose.slides/presentation) do PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Převádí [`Presentation`](../../aspose.slides/presentation) do PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Převádí [`Presentation`](../../aspose.slides/presentation) do PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Převádí [`Presentation`](../../aspose.slides/presentation) do PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je název výstupního souboru zadán jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je název výstupního souboru zadán jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je název výstupního souboru zadán jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Převádí [`Presentation`](../../aspose.slides/presentation) do SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Převádí [`Presentation`](../../aspose.slides/presentation) do SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Převádí [`Presentation`](../../aspose.slides/presentation) do SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Převádí [`Presentation`](../../aspose.slides/presentation) do SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Převádí [`Presentation`](../../aspose.slides/presentation) do SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Převádí vstupní prezentaci na sadu obrázků ve formátu TIFF. Pokud je název výstupního souboru zadán jako "myPath/myFilename.tiff", výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N je číslo snímku. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Převádí vstupní prezentaci do formátu TIFF s vlastními možnostmi. Pokud je název výstupního souboru zadán jako "myPath/myFilename.tiff" a *multipage* je `false`, výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N je číslo snímku. V opačném případě, pokud je *multipage* `true`, výsledek bude vícestránkový dokument "myPath/myFilename.tiff". |

## Ostatní členové

| Název | Popis |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Zpětné volání, které bude vyvoláno pro každý [`Slide`](../../aspose.slides/slide), očekávaná výstupní cesta má být vrácena. |

### Příklady

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Viz také

* jmenný prostor [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->