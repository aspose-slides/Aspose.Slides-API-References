---
title: ITiffOptions
second_title: Referencia de API de Aspose.Sildes para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.
type: docs
weight: 4000
url: /es/aspose.slides.export/itiffoptions/
---

## Interfaz ITiffOptions

Proporciona opciones que controlan cómo se guarda una presentación en formato TIFF.

```csharp
public interface ITiffOptions : ISaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/itiffoptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura [`ISaveOptions`](../isaveoptions). |
| [BwConversionMode](../../aspose.slides.export/itiffoptions/bwconversionmode) { get; set; } | Especifica el algoritmo para convertir una imagen a color en una imagen en blanco y negro. Esta opción se aplicará solo si [`CompressionType`](./compressiontype) está configurado en CCITT4 o CCITT3. Lectura/escritura [`BlackWhiteConversionMode`](../blackwhiteconversionmode). El valor predeterminado es Default. |
| [CompressionType](../../aspose.slides.export/itiffoptions/compressiontype) { get; set; } | Especifica el tipo de compresión. Lectura/escritura [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DpiX](../../aspose.slides.export/itiffoptions/dpix) { get; set; } | Especifica la resolución horizontal en puntos por pulgada. Lectura/escritura UInt32. |
| [DpiY](../../aspose.slides.export/itiffoptions/dpiy) { get; set; } | Especifica la resolución vertical en puntos por pulgada. Lectura/escritura UInt32. |
| [ImageSize](../../aspose.slides.export/itiffoptions/imagesize) { get; set; } | Especifica el tamaño de una imagen TIFF generada. El valor predeterminado es 0x0, lo que significa que los tamaños de las imágenes generadas se calcularán en función del tamaño de la diapositiva de la presentación. Lectura/escritura Size. |
| [InkOptions](../../aspose.slides.export/itiffoptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/itiffoptions/pixelformat) { get; set; } | Especifica el formato de píxel para las imágenes generadas. Lectura/escritura [`ImagePixelFormat`](../imagepixelformat). |
| [ShowHiddenSlides](../../aspose.slides.export/itiffoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/itiffoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |

### Véase también

* interfaz [ISaveOptions](../isaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->