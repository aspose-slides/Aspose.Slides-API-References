---
title: TiffOptions
second_title: Aspose.Sildes para la referencia de la API .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.
type: docs
weight: 4570
url: /es/aspose.slides.export/tiffoptions/
---
## TiffOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffOptions](tiffoptions)() | Constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción se aplicará solo si [`CompressionType`](./compressiontype) está configurado a CCITT4 o CCITT3 Lectura/escritura [`BlackWhiteConversionMode`](../blackwhiteconversionmode). El valor predeterminado es Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Especifica el tipo de compresión. Lectura/escritura [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente origen. Lectura-escritura String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Especifica la resolución horizontal en puntos por pulgada. Lectura/escritura UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Especifica la resolución vertical en puntos por pulgada. Lectura/escritura UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de imágenes generadas se calcularán en función del valor del tamaño de la diapositiva de la presentación. Lectura/escritura Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Especifica el formato de píxel para las imágenes generadas. Lectura/escritura [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para actualizaciones del progreso de guardado en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

El siguiente ejemplo muestra cómo convertir PowerPoint a TIFF con el tamaño predeterminado.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Guardando la presentación en un documento TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a TIFF con un tamaño personalizado.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instanciar la clase TiffOptions
    TiffOptions opts = new TiffOptions();
    // Establecer el tipo de compresión
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Tipos de compresión
    // Default - Especifica el esquema de compresión predeterminado (LZW).
    // None - Especifica que no hay compresión.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // La profundidad depende del tipo de compresión y no puede establecerse manualmente.
    // La unidad de resolución siempre es igual a "2" (puntos por pulgada)
    // Estableciendo DPI de la imagen
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Establecer tamaño de la imagen
    opts.ImageSize = new Size(1728, 1078);
    // Guardar la presentación en TIFF con el tamaño de imagen especificado
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

El siguiente ejemplo muestra cómo convertir PowerPoint a TIFF con un formato de píxel de imagen personalizado.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat contiene los siguientes valores (según la documentación):
    Format1bppIndexed; // 1 bits por pixel, indexado.
    Format4bppIndexed; // 4 bits por pixel, indexado.
    Format8bppIndexed; // 8 bits por pixel, indexado.
    Format24bppRgb; // 24 bits por pixel, RGB.
    Format32bppArgb; // 32 bits por pixel, ARGB.
    */
    // Guardar la presentación en TIFF con el tamaño de imagen especificado
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Ver también

* clase [SaveOptions](../saveoptions)
* interfaz [ITiffOptions](../itiffoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->