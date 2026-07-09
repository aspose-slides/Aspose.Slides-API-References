---
title: Convert
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Gruppe von Methoden dar, die zum Konvertieren von Presentation../aspose.slides/presentation bestimmt sind.
type: docs
weight: 7880
url: /de/aspose.slides.lowcode/convert/
---
## Convert class

Stellt eine Gruppe von Methoden dar, die zum Konvertieren von [`Presentation`](../../aspose.slides/presentation) bestimmt sind.

```csharp
public static class Convert
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) mithilfe der übergebenen Ausgabepfad-Erweiterung, um das erforderliche Exportformat zu bestimmen. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Konvertiert die Eingabepräsentation in eine Menge von JPEG-Bildern. Wird der Ausgabedateiname als „myPath/myFilename.jpeg“ angegeben, wird das Ergebnis als Menge von „myPath/myFilename_N.jpeg“-Dateien gespeichert, wobei N die Foliennummer ist. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Konvertiert die Eingabepräsentation in eine Menge von JPEG-Bildern. Wird der Ausgabedateiname als „myPath/myFilename.jpeg“ angegeben, wird das Ergebnis als Menge von „myPath/myFilename_N.jpeg“-Dateien gespeichert, wobei N die Foliennummer ist. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Konvertiert die Eingabepräsentation in eine Menge von JPEG-Bildern. Wird der Ausgabedateiname als „myPath/myFilename.jpeg“ angegeben, wird das Ergebnis als Menge von „myPath/myFilename_N.jpeg“-Dateien gespeichert, wobei N die Foliennummer ist. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Konvertiert die Eingabepräsentation in eine Menge von PNG-Bildern. Wird der Ausgabedateiname als „myPath/myFilename.png“ angegeben, wird das Ergebnis als Menge von „myPath/myFilename_N.png“-Dateien gespeichert, wobei N die Foliennummer ist. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Konvertiert die Eingabepräsentation in eine Menge von PNG-Bildern. Wird der Ausgabedateiname als „myPath/myFilename.png“ angegeben, wird das Ergebnis als Menge von „myPath/myFilename_N.png“-Dateien gespeichert, wobei N die Foliennummer ist. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Konvertiert die Eingabepräsentation in eine Menge von PNG-Bildern. Wird der Ausgabedateiname als „myPath/myFilename.png“ angegeben, wird das Ergebnis als Menge von „myPath/myFilename_N.png“-Dateien gespeichert, wobei N die Foliennummer ist. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Konvertiert die Eingabepräsentation in eine Menge von TIFF-Bildern. Wird der Ausgabedateiname als „myPath/myFilename.tiff“ angegeben, wird das Ergebnis als Menge von „myPath/myFilename_N.tiff“-Dateien gespeichert, wobei N die Foliennummer ist. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Konvertiert die Eingabepräsentation in das TIFF-Format mit benutzerdefinierten Optionen. Wird der Ausgabedateiname als „myPath/myFilename.tiff“ angegeben und *multipage* ist `false`, wird das Ergebnis als Menge von „myPath/myFilename_N.tiff“-Dateien gespeichert, wobei N die Foliennummer ist. Ist *multipage* hingegen `true`, entsteht ein mehrseitiges Dokument „myPath/myFilename.tiff“. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback, der für jedes [`Slide`](../../aspose.slides/slide) aufgerufen wird, wobei der Ausgabepfad zurückgegeben werden soll. |

### Beispiele

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Siehe auch

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->