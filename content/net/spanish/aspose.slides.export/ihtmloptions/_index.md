---
title: IHtmlOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa opciones de exportación HTML.
type: docs
weight: 3800
url: /es/aspose.slides.export/ihtmloptions/
---

## Interfaz IHtmlOptions

Representa opciones de exportación HTML.

```csharp
public interface IHtmlOptions : ISaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/ihtmloptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura [`ISaveOptions`](../isaveoptions). |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/ihtmloptions/deletepicturescroppedareas) { get; set; } | Un valor booleano que indica si las partes recortadas permanecen como parte del documento. Si es verdadero, las partes recortadas serán eliminadas; si es falso, se serializarán en el documento (lo que puede llevar a un archivo más grande). Lectura/escritura Booleano. |
| [DisableFontLigatures](../../aspose.slides.export/ihtmloptions/disablefontligatures) { get; set; } | Obtiene o establece un valor que indica si el texto se renderiza sin utilizar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en `false`. |
| [HtmlFormatter](../../aspose.slides.export/ihtmloptions/htmlformatter) { get; set; } | Devuelve o establece la plantilla HTML. Lectura/escritura [`IHtmlFormatter`](../ihtmlformatter). |
| [InkOptions](../../aspose.slides.export/ihtmloptions/inkoptions) { get; } | Proporciona opciones que controlan la apariencia de los objetos de tinta en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ihtmloptions/jpegquality) { get; set; } | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura Byte. |
| [PicturesCompression](../../aspose.slides.export/ihtmloptions/picturescompression) { get; set; } | Representa el nivel de compresión de las imágenes. Lectura/escritura [`PicturesCompression`](./picturescompression). |
| [ShowHiddenSlides](../../aspose.slides.export/ihtmloptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir slides ocultas o no. Por defecto es `false`. |
| [SlideImageFormat](../../aspose.slides.export/ihtmloptions/slideimageformat) { get; set; } | Devuelve o establece opciones de formato de imagen de slide. Lectura/escritura [`ISlideImageFormat`](../islideimageformat). |
| [SlidesLayoutOptions](../../aspose.slides.export/ihtmloptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en el que se colocan los slides en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SvgResponsiveLayout](../../aspose.slides.export/ihtmloptions/svgresponsivelayout) { get; set; } | Verdadero para excluir los atributos de ancho y alto del contenedor SVG - eso hará que el diseño sea responsivo. Falso - de lo contrario. Lectura/escritura Booleano. |

### También Vea

* interfaz [ISaveOptions](../isaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->