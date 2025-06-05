---
title: TiffOptions
second_title: Aspose.Sildes for .NET API Reference
description: Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.
type: docs
weight: 4380
url: /es/aspose.slides.export/tiffoptions/
---

## TiffOptions class

Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Constructor predeterminado. |

## Properties

| Name | Description |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción se aplicará solo si [`CompressionType`](./compressiontype) está configurado en CCITT4 o CCITT3 Leer/escribir [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Predeterminado es Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Especifica el tipo de compresión. Leer/escribir [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Leer-escribir String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Especifica la resolución horizontal en puntos por pulgada. Leer/escribir UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Especifica la resolución vertical en puntos por pulgada. Leer/escribir UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del gradiente. Leer/escribir [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de imagen generados se calcularán en función del tamaño de la diapositiva de la presentación. Leer/escribir Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Especifica el formato de píxel para las imágenes generadas. Leer/escribir [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de callback para actualizar el progreso de guardado en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. Predeterminado es `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Leer/escribir Boolean. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Leer/escribir [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Examples

El siguiente ejemplo muestra cómo convertir PowerPoint a TIFF con tamaño predeterminado.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Guardar la presentación como documento TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a TIFF con tamaño personalizado.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instanciar la clase TiffOptions
    TiffOptions opts = new TiffOptions();
    // Configurando el tipo de compresión
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Tipos de compresión
    // Default - Especifica el esquema de compresión predeterminado (LZW).
    // None - Especifica sin compresión.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // La profundidad depende del tipo de compresión y no se puede establecer manualmente.
    // La unidad de resolución siempre es igual a “2” (puntos por pulgada)
    // Configurando DPI de imagen
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Establecer tamaño de imagen
    opts.ImageSize = new Size(1728, 1078);
    // Guardar la presentación en TIFF con tamaño de imagen especificado
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a TIFF con formato de píxel de imagen personalizado.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat contiene los siguientes valores (como se puede ver en la documentación):
    Format1bppIndexed; // 1 bits por píxel, indexado.
    Format4bppIndexed; // 4 bits por píxel, indexado.
    Format8bppIndexed; // 8 bits por píxel, indexado.
    Format24bppRgb; // 24 bits por píxel, RGB.
    Format32bppArgb; // 32 bits por píxel, ARGB.
    */
    // Guardar la presentación en TIFF con formato de píxel de imagen especificado
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### See Also

* class [SaveOptions](../saveoptions)
* interface [ITiffOptions](../itiffoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->