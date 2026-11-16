---
title: Convert
second_title: Aspose.Sildes .NET API referenciája
description: A Presentation../aspose.slides/presentation átalakítására szánt metóduscsoportot képviseli.
type: docs
weight: 7900
url: /hu/aspose.slides.lowcode/convert/
---
## Konvertáló osztály

A [`Presentation`](../../aspose.slides/presentation) átalakítására szánt metóduscsoportot képviseli.

```csharp
public static class Convert
```

## Metódusok

| Név | Leírás |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | [`Presentation`](../../aspose.slides/presentation) átalakítását a megadott kimeneti útvonal kiterjesztésével végzi, hogy meghatározza a szükséges export formátumot. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Átalakítja a bemeneti prezentációt JPEG formátumú képek halmazává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formátumban van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok halmazaként lesz mentve, ahol N a dia száma. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Átalakítja a bemeneti prezentációt JPEG formátumú képek halmazává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formátumban van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok halmazaként lesz mentve, ahol N a dia száma. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Átalakítja a bemeneti prezentációt JPEG formátumú képek halmazává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formátumban van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok halmazaként lesz mentve, ahol N a dia száma. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | [`Presentation`](../../aspose.slides/presentation) PDF formátumba alakítja. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Átalakítja a bemeneti prezentációt PNG formátumú képek halmazává. Ha a kimeneti fájlnév "myPath/myFilename.png" formátumban van megadva, az eredmény "myPath/myFilename_N.png" fájlok halmazaként lesz mentve, ahol N a dia száma. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Átalakítja a bemeneti prezentációt PNG formátumú képek halmazává. Ha a kimeneti fájlnév "myPath/myFilename.png" formátumban van megadva, az eredmény "myPath/myFilename_N.png" fájlok halmazaként lesz mentve, ahol N a dia száma. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Átalakítja a bemeneti prezentációt PNG formátumú képek halmazává. Ha a kimeneti fájlnév "myPath/myFilename.png" formátumban van megadva, az eredmény "myPath/myFilename_N.png" fájlok halmazaként lesz mentve, ahol N a dia száma. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | [`Presentation`](../../aspose.slides/presentation) SVG formátumba alakítja. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Átalakítja a bemeneti prezentációt TIFF formátumú képek halmazává. Ha a kimeneti fájlnév "myPath/myFilename.tiff" formátumban van megadva, az eredmény "myPath/myFilename_N.tiff" fájlok halmazaként lesz mentve, ahol N a dia száma. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Átalakítja a bemeneti prezentációt TIFF formátumba egyéni beállításokkal. Ha a kimeneti fájlnév "myPath/myFilename.tiff" és a *multipage* értéke `false`, az eredmény "myPath/myFilename_N.tiff" fájlok halmazaként lesz mentve, ahol N a dia száma. Ellenkező esetben, ha a *multipage* értéke `true`, az eredmény egy többoldalas "myPath/myFilename.tiff" dokumentum lesz. |

## Egyéb tagok

| Név | Leírás |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Visszahívás, amely minden egyes [`Slide`](../../aspose.slides/slide) esetén meghívásra kerül, és a kimeneti útvonalat adja vissza. |

### Példák

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Lásd még

* névtér [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->