---  
title: TiffOptions  
second_title: Referencia de la API Aspose.Slides para .NET  
description: Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.
type: docs  
weight: 4380  
url: /es/aspose.slides.export/tiffoptions/
---  

## Clase TiffOptions  

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
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Especifica el algoritmo para convertir una imagen de color en una imagen en blanco y negro. Esta opción se aplicará solo si [`CompressionType`](./compressiontype) está configurado en CCITT4 o CCITT3. Lectura/escritura [`BlackWhiteConversionMode`](../blackwhiteconversionmode). El valor predeterminado es Default. |  
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Especifica el tipo de compresión. Lectura/escritura [`TiffCompressionTypes`](../tiffcompressiontypes). |  
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Lectura/escritura String. |  
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Especifica la resolución horizontal en puntos por pulgada. Lectura/escritura UInt32. |  
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Especifica la resolución vertical en puntos por pulgada. Lectura/escritura UInt32. |  
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |  
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de imagen generados se calcularán en función del tamaño de la diapositiva de la presentación. Lectura/escritura Size. |  
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |  
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Especifica el formato de píxeles para las imágenes generadas. Lectura/escritura [`ImagePixelFormat`](../imagepixelformat). |  
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |  
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |  
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **false**. |  
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |  
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |  

### Ejemplos  

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
    // Establecer el tipo de compresión  
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
    // La unidad de resolución es siempre igual a “2” (puntos por pulgada)  
    // Establecer DPI de imagen  
    opts.DpiX = 200;  
    opts.DpiY = 100;  
    // Establecer tamaño de imagen  
    opts.ImageSize = new Size(1728, 1078);  
    // Guardar la presentación como TIFF con el tamaño de imagen especificado  
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);  
}  
```  

El siguiente ejemplo muestra cómo convertir PowerPoint a TIFF con un formato de píxel de imagen personalizado.  

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
    // Guardar la presentación como TIFF con el formato de píxel de imagen especificado  
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);  
}  
```  

### Ver También  

* clase [SaveOptions](../saveoptions)  
* interfaz [ITiffOptions](../itiffoptions)  
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)  
* ensamblaje [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  