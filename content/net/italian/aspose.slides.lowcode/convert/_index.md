---
title: Convert
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un gruppo di metodi destinati a convertire Presentation../aspose.slides/presentation.
type: docs
weight: 7860
url: /it/aspose.slides.lowcode/convert/
---
## classe Convert

Rappresenta un gruppo di metodi destinati a convertire [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Converte [`Presentation`](../../aspose.slides/presentation) usando l’estensione del percorso di output fornita per determinare il formato di esportazione richiesto. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Converte la presentazione di input in un set di immagini in formato JPEG. Se il nome del file di output è specificato come "myPath/myFilename.jpeg", il risultato verrà salvato come un set di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Converte la presentazione di input in un set di immagini in formato JPEG. Se il nome del file di output è specificato come "myPath/myFilename.jpeg", il risultato verrà salvato come un set di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Converte la presentazione di input in un set di immagini in formato JPEG. Se il nome del file di output è specificato come "myPath/myFilename.jpeg", il risultato verrà salvato come un set di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Converte [`Presentation`](../../aspose.slides/presentation) in PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Converte [`Presentation`](../../aspose.slides/presentation) in PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Converte [`Presentation`](../../aspose.slides/presentation) in PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Converte [`Presentation`](../../aspose.slides/presentation) in PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Converte la presentazione di input in un set di immagini in formato PNG. Se il nome del file di output è specificato come "myPath/myFilename.png", il risultato verrà salvato come un set di file "myPath/myFilename_N.png", dove N è il numero della diapositiva. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Converte la presentazione di input in un set di immagini in formato PNG. Se il nome del file di output è specificato come "myPath/myFilename.png", il risultato verrà salvato come un set di file "myPath/myFilename_N.png", dove N è il numero della diapositiva. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Converte la presentazione di input in un set di immagini in formato PNG. Se il nome del file di output è specificato come "myPath/myFilename.png", il risultato verrà salvato come un set di file "myPath/myFilename_N.png", dove N è il numero della diapositiva. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Converte [`Presentation`](../../aspose.slides/presentation) in SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Converte [`Presentation`](../../aspose.slides/presentation) in SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Converte [`Presentation`](../../aspose.slides/presentation) in SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Converte [`Presentation`](../../aspose.slides/presentation) in SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Converte [`Presentation`](../../aspose.slides/presentation) in SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Converte la presentazione di input in un set di immagini in formato TIFF. Se il nome del file di output è specificato come "myPath/myFilename.tiff", il risultato verrà salvato come un set di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Converte la presentazione di input in formato TIFF con opzioni personalizzate. Se il nome del file di output è specificato come "myPath/myFilename.tiff" e *multipage* è `false`, il risultato verrà salvato come un set di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva. Altrimenti, se *multipage* è `true`, il risultato sarà un documento multipagina "myPath/myFilename.tiff". |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback che verrà invocata per ogni [`Slide`](../../aspose.slides/slide), si prevede che venga restituito il percorso di output. |

### Esempi

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Vedere anche

* spazio dei nomi [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->