---
title: Convert
second_title: Aspose.Sildes a .NET API referenciához
description: A Presentation../aspose.slides/presentation átalakítására szolgáló metóduscsoportot képviseli.
type: docs
weight: 7880
url: /hu/aspose.slides.lowcode/convert/
---
## Convert osztály

A [`Presentation`](../../aspose.slides/presentation) átalakítására szolgáló metódusok csoportját képviseli.

```csharp
public static class Convert
```

## Metódusok

| Név | Leírás |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | [`Presentation`](../../aspose.slides/presentation) átalakítja a megadott kimeneti útvonal kiterjesztését felhasználva a szükséges exportformátum meghatározásához. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Az input prezentációt JPEG formátumú képek halmazává alakítja. Ha a kimeneti fájlnév "myPath/myFilename.jpeg"-ként van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok halmazaként kerül mentésre, ahol N a dia száma. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Az input prezentációt JPEG formátumú képek halmazává alakítja. Ha a kimeneti fájlnév "myPath/myFilename.jpeg"-ként van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok halmazaként kerül mentésre, ahol N a dia száma. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Az input prezentációt JPEG formátumú képek halmazává alakítja. Ha a kimeneti fájlnév "myPath/myFilename.jpeg"-ként van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok halmazaként kerül mentésre, ahol N a dia száma. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Az input prezentációt PNG formátumú képek halmazává alakítja. Ha a kimeneti fájlnév "myPath/myFilename.png"-ként van megadva, az eredmény "myPath/myFilename_N.png" fájlok halmazaként kerül mentésre, ahol N a dia száma. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Az input prezentációt PNG formátumú képek halmazává alakítja. Ha a kimeneti fájlnév "myPath/myFilename.png"-ként van megadva, az eredmény "myPath/myFilename_N.png" fájlok halmazaként kerül mentésre, ahol N a dia száma. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Az input prezentációt PNG formátumú képek halmazává alakítja. Ha a kimeneti fájlnév "myPath/myFilename.png"-ként van megadva, az eredmény "myPath/myFilename_N.png" fájlok halmazaként kerül mentésre, ahol N a dia száma. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Az input prezentációt TIFF formátumú képek halmazává alakítja. Ha a kimeneti fájlnév "myPath/myFilename.tiff"-ként van megadva, az eredmény "myPath/myFilename_N.tiff" fájlok halmazaként kerül mentésre, ahol N a dia száma. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Az input prezentációt egyedi beállításokkal TIFF formátumba alakítja. Ha a kimeneti fájlnév "myPath/myFilename.tiff"-ként van megadva és a *multipage* `false`, az eredmény "myPath/myFilename_N.tiff" fájlok halmazaként kerül mentésre, ahol N a dia száma. Ellenkező esetben, ha a *multipage* `true`, az eredmény egy többoldalas "myPath/myFilename.tiff" dokumentum lesz. |

## Egyéb tagok

| Név | Leírás |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Visszahívás, amely minden [`Slide`](../../aspose.slides/slide) esetén meghívásra kerül, a visszaadandó kimeneti útvonalat várva. |

### Példák

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Lásd még

* névtér [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->