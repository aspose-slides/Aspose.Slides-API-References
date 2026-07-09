---
title: Convert
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa un grupo de métodos destinados a convertir Presentation../aspose.slides/presentation.
type: docs
weight: 7880
url: /es/aspose.slides.lowcode/convert/
---
## Convert clase

Representa un grupo de métodos destinados a convertir [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Convert
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | Convierte [`Presentation`](../../aspose.slides/presentation) usando la extensión de ruta de salida proporcionada para determinar el formato de exportación requerido. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg)(Presentation, string) | Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_2)(Presentation, string, Size) | Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva. |
| static [ToJpeg](../../aspose.slides.lowcode/convert/tojpeg#tojpeg_1)(Presentation, string, float, IRenderingOptions) | Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | Convierte [`Presentation`](../../aspose.slides/presentation) a PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | Convierte [`Presentation`](../../aspose.slides/presentation) a PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | Convierte [`Presentation`](../../aspose.slides/presentation) a PDF. |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | Convierte [`Presentation`](../../aspose.slides/presentation) a PDF. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng)(Presentation, string) | Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.png", donde N es el número de diapositiva. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_2)(Presentation, string, Size) | Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.png", donde N es el número de diapositiva. |
| static [ToPng](../../aspose.slides.lowcode/convert/topng#topng_1)(Presentation, string, float, IRenderingOptions) | Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.png", donde N es el número de diapositiva. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | Convierte [`Presentation`](../../aspose.slides/presentation) a SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | Convierte [`Presentation`](../../aspose.slides/presentation) a SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | Convierte [`Presentation`](../../aspose.slides/presentation) a SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | Convierte [`Presentation`](../../aspose.slides/presentation) a SVG. |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | Convierte [`Presentation`](../../aspose.slides/presentation) a SVG. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff)(Presentation, string) | Convierte la presentación de entrada en un conjunto de imágenes en formato TIFF. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.tiff", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.tiff", donde N es el número de diapositiva. |
| static [ToTiff](../../aspose.slides.lowcode/convert/totiff#totiff_1)(Presentation, string, ITiffOptions, bool) | Convierte la presentación de entrada al formato TIFF con opciones personalizadas. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.tiff" y *multipage* es `false`, el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.tiff", donde N es el número de diapositiva. En caso contrario, si *multipage* es `true`, el resultado será un documento multipágina "myPath/myFilename.tiff". |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) | Callback que se invocará para cada [`Slide`](../../aspose.slides/slide), se espera que devuelva la ruta de salida. |

### Ejemplos

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### Ver también

* espacio de nombres [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->