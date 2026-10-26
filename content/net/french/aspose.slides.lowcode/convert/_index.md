---
title: Convert
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente un groupe de méthodes destinées à convertir Presentation../aspose.slides/presentation.
type: docs
weight: 7880
url: /fr/aspose.slides.lowcode/convert/
---
## Classe Convert

Représente un groupe de méthodes destinées à convertir [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Convertit [`Presentation`](../../aspose.slides/presentation) en utilisant l'extension du chemin de sortie fournie pour déterminer le format d'exportation requis. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Convertit [`Presentation`](../../aspose.slides/presentation) en PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Convertit [`Presentation`](../../aspose.slides/presentation) en PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Convertit [`Presentation`](../../aspose.slides/presentation) en PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Convertit [`Presentation`](../../aspose.slides/presentation) en PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Convertit [`Presentation`](../../aspose.slides/presentation) en SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Convertit [`Presentation`](../../aspose.slides/presentation) en SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Convertit [`Presentation`](../../aspose.slides/presentation) en SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Convertit [`Presentation`](../../aspose.slides/presentation) en SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Convertit [`Presentation`](../../aspose.slides/presentation) en SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Convertit la présentation d'entrée en un ensemble d'images au format TIFF. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.tiff", le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.tiff", où N est le numéro d'une diapositive. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Convertit la présentation d'entrée en format TIFF avec des options personnalisées. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.tiff" et que *multipage* est `false`, le résultat sera enregistré sous la forme d'un ensemble de fichiers "myPath/myFilename_N.tiff", où N est le numéro d'une diapositive. Sinon, si *multipage* est `true`, le résultat sera un document multi-pages "myPath/myFilename.tiff". |

## Autres membres

| Nom | Description |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Rappel qui sera invoqué pour chaque [`Slide`](../../aspose.slides/slide), le chemin de sortie devant être renvoyé. |

### Exemples

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Voir aussi

* espace de noms [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->