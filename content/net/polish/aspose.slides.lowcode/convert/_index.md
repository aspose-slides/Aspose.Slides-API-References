---
title: Convert
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje grupę metod przeznaczonych do konwertowania Presentation../aspose.slides/presentation.
type: docs
weight: 7860
url: /pl/aspose.slides.lowcode/convert/
---
## Convert klasa

Reprezentuje grupę metod przeznaczonych do konwertowania [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Metody

| Nazwa | Opis |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Konwertuje [`Presentation`](../../aspose.slides/presentation) używając podanego rozszerzenia ścieżki wyjściowej w celu określenia wymaganego formatu eksportu. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Konwertuje wejściową prezentację na zestaw obrazów w formacie PNG. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Konwertuje wejściową prezentację na zestaw obrazów w formacie PNG. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Konwertuje wejściową prezentację na zestaw obrazów w formacie PNG. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Konwertuje [`Presentation`](../../aspose.slides/presentation) do formatu SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Konwertuje wejściową prezentację na zestaw obrazów w formacie TIFF. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.tiff", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Konwertuje wejściową prezentację do formatu TIFF z niestandardowymi opcjami. Jeśli nazwa pliku wyjściowego jest podana jako "myPath/myFilename.tiff" i *multipage* jest `false`, wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu. W przeciwnym razie, jeśli *multipage* jest `true`, wynik będzie wielostronicowym dokumentem "myPath/myFilename.tiff". |

## Inne członkowie

| Nazwa | Opis |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Wywołanie zwrotne, które zostanie wywołane dla każdego [`Slide`](../../aspose.slides/slide), oczekując zwrócenia ścieżki wyjściowej. |

### Przykłady

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Zobacz także

* przestrzeń nazw [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->