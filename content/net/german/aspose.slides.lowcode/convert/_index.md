---
title: Convert
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, Presentation../aspose.slides/presentation zu konvertieren.
type: docs
weight: 7900
url: /de/aspose.slides.lowcode/convert/
---
## Convert Klasse

Represents a group of methods intended to convert [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) mithilfe der übergebenen Ausgabepfade-Erweiterung, um das erforderliche Exportformat zu bestimmen. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Konvertiert die Eingabepräsentation in einen Satz von JPEG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N eine Foliennummer ist. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Konvertiert die Eingabepräsentation in einen Satz von JPEG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N eine Foliennummer ist. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Konvertiert die Eingabepräsentation in einen Satz von JPEG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N eine Foliennummer ist. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Konvertiert die Eingabepräsentation in einen Satz von PNG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N eine Foliennummer ist. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Konvertiert die Eingabepräsentation in einen Satz von PNG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N eine Foliennummer ist. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Konvertiert die Eingabepräsentation in einen Satz von PNG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N eine Foliennummer ist. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Konvertiert [`Presentation`](../../aspose.slides/presentation) zu SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Konvertiert die Eingabepräsentation in einen Satz von TIFF-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.tiff" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.tiff"-Dateien gespeichert, wobei N eine Foliennummer ist. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Konvertiert die Eingabepräsentation in das TIFF-Format mit benutzerdefinierten Optionen. Wenn der Ausgabedateiname als "myPath/myFilename.tiff" angegeben wird und *multipage* `false` ist, wird das Ergebnis als ein Satz von "myPath/myFilename_N.tiff"-Dateien gespeichert, wobei N eine Foliennummer ist. Andernfalls, wenn *multipage* `true` ist, wird das Ergebnis ein mehrseitiges "myPath/myFilename.tiff"-Dokument sein. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback, der für jedes [`Slide`](../../aspose.slides/slide) aufgerufen wird, wobei der Ausgabepfad zurückgegeben werden soll. |

### Beispiele

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Siehe auch

* Namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->