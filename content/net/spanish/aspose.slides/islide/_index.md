---
title: ISlide
second_title: Aspose.Sildes para .NET Referencia de la API
description: Representa una diapositiva en una presentación.
type: docs
weight: 6820
url: /es/aspose.slides/islide/
---

## Interfaz ISlide

Representa una diapositiva en una presentación.

```csharp
public interface ISlide : IBaseSlide, IOverrideThemeable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIBaseSlide](../../aspose.slides/islide/asibaseslide) { get; } | Permite obtener la interfaz base IBaseSlide. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [AsIOverrideThemeable](../../aspose.slides/islide/asioverridethemeable) { get; } | Devuelve la interfaz IOverrideThemeable. Solo lectura [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [HeaderFooterManager](../../aspose.slides/islide/headerfootermanager) { get; } | Devuelve el administrador de encabezados y pies de página de la diapositiva. Solo lectura [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/islide/hidden) { get; set; } | Determina si la diapositiva especificada está oculta durante una presentación. Lectura/escritura Boolean. |
| [LayoutSlide](../../aspose.slides/islide/layoutslide) { get; set; } | Devuelve o establece la diapositiva de diseño para la diapositiva actual. Lectura/escritura [`ILayoutSlide`](../ilayoutslide). |
| [NotesSlideManager](../../aspose.slides/islide/notesslidemanager) { get; } | Permite acceder a la diapositiva de notas, agregarla y eliminarla. Solo lectura [`INotesSlideManager`](../inotesslidemanager). |
| [SlideNumber](../../aspose.slides/islide/slidenumber) { get; set; } | Devuelve el número de la diapositiva. El índice de la diapositiva en la colección [`Slides`](../ipresentation/slides) siempre es igual a SlideNumber - 1. Lectura/escritura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetImage](../../aspose.slides/islide/getimage#getimage)() | Devuelve un objeto de imagen en miniatura (20% del tamaño real). |
| [GetImage](../../aspose.slides/islide/getimage#getimage_1)(IRenderingOptions) | Devuelve un objeto de imagen en miniatura tipo Bitmap. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_4)(ITiffOptions) | Devuelve un objeto de imagen en miniatura tipo tiff con los parámetros especificados. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_6)(Size) | Devuelve un objeto de imagen con el tamaño especificado. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_5)(float, float) | Devuelve un objeto de imagen con escalado personalizado. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_3)(IRenderingOptions, Size) | Devuelve un objeto de imagen en miniatura tipo Bitmap con el tamaño especificado. |
| [GetImage](../../aspose.slides/islide/getimage#getimage_2)(IRenderingOptions, float, float) | Devuelve un objeto de imagen en miniatura tipo Bitmap con escalado personalizado. |
| [GetSlideComments](../../aspose.slides/islide/getslidecomments)(ICommentAuthor) | Devuelve todos los comentarios de la diapositiva añadidos por un autor específico. |
| [Remove](../../aspose.slides/islide/remove)() | Elimina la diapositiva de la presentación. |
| [Reset](../../aspose.slides/islide/reset)() | Restablece la posición, tamaño y formato de cada forma que tenga un prototipo en LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/islide/writeasemf)(Stream) | Guarda el contenido de la diapositiva como un archivo EMF. |
| [WriteAsSvg](../../aspose.slides/islide/writeassvg#writeassvg)(Stream) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [WriteAsSvg](../../aspose.slides/islide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Guarda el contenido de la diapositiva como un archivo SVG. |

### Véase también

* interfaz [IBaseSlide](../ibaseslide)
* interfaz [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->