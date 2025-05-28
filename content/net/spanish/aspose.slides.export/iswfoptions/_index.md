---
title: ISwfOptions
second_title: Aspose.Sildes para .NET Referencia de API
description: Proporciona opciones que controlan cómo se guarda una presentación en formato SWF.
type: docs
weight: 3980
url: /es/aspose.slides.export/iswfoptions/
---

## Interfaz ISwfOptions

Proporciona opciones que controlan cómo se guarda una presentación en formato SWF.

```csharp
public interface ISwfOptions : ISaveOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export/iswfoptions/asisaveoptions) { get; } | Devuelve la interfaz ISaveOptions. Solo lectura [`ISaveOptions`](../isaveoptions). |
| [Compressed](../../aspose.slides.export/iswfoptions/compressed) { get; set; } | Especifica si el documento SWF generado debe ser comprimido o no. El valor predeterminado es `true`. |
| [EnableContextMenu](../../aspose.slides.export/iswfoptions/enablecontextmenu) { get; set; } | Habilitar/deshabilitar el menú contextual. El valor predeterminado es verdadero. |
| [JpegQuality](../../aspose.slides.export/iswfoptions/jpegquality) { get; set; } | Especifica la calidad de las imágenes JPEG. El valor predeterminado es 95. |
| [LogoImageBytes](../../aspose.slides.export/iswfoptions/logoimagebytes) { get; set; } | Imagen que se mostrará como logo en la esquina superior derecha del visualizador. La imagen debe ser un PNG de 32x64 píxeles, de lo contrario, el logo puede mostrarse incorrectamente. |
| [LogoLink](../../aspose.slides.export/iswfoptions/logolink) { get; set; } | Obtiene o establece la dirección de hipervínculo completa para un logo. Tiene efecto solo si se especifica un [`LogoImageBytes`](./logoimagebytes). |
| [ShowBottomPane](../../aspose.slides.export/iswfoptions/showbottompane) { get; set; } | Mostrar/ocultar el panel inferior. Puede ser anulado en flashvars. El valor predeterminado es verdadero. |
| [ShowFullScreen](../../aspose.slides.export/iswfoptions/showfullscreen) { get; set; } | Mostrar/ocultar el botón de pantalla completa. Puede ser anulado en flashvars. El valor predeterminado es verdadero. |
| [ShowHiddenSlides](../../aspose.slides.export/iswfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [ShowLeftPane](../../aspose.slides.export/iswfoptions/showleftpane) { get; set; } | Mostrar/ocultar el panel izquierdo. Puede ser anulado en flashvars. El valor predeterminado es verdadero. |
| [ShowPageBorder](../../aspose.slides.export/iswfoptions/showpageborder) { get; set; } | Especifica si se debe mostrar un borde alrededor de las páginas. El valor predeterminado es verdadero. |
| [ShowPageStepper](../../aspose.slides.export/iswfoptions/showpagestepper) { get; set; } | Mostrar/ocultar el selector de páginas. Puede ser anulado en flashvars. El valor predeterminado es verdadero. |
| [ShowSearch](../../aspose.slides.export/iswfoptions/showsearch) { get; set; } | Mostrar/ocultar la sección de búsqueda. Puede ser anulado en flashvars. El valor predeterminado es verdadero. |
| [ShowTopPane](../../aspose.slides.export/iswfoptions/showtoppane) { get; set; } | Mostrar/ocultar todo el panel superior. Puede ser anulado en flashvars. El valor predeterminado es verdadero. |
| [SlidesLayoutOptions](../../aspose.slides.export/iswfoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). Esta propiedad no admite la asignación de objetos del tipo `Aspose.Slides.Export.HandoutLayoutingOptions` |
| [StartOpenLeftPane](../../aspose.slides.export/iswfoptions/startopenleftpane) { get; set; } | Comenzar con el panel izquierdo abierto. Puede ser anulado en flashvars. El valor predeterminado es falso. |
| [ViewerIncluded](../../aspose.slides.export/iswfoptions/viewerincluded) { get; set; } | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es `true`. |

### Véase también

* interfaz [ISaveOptions](../isaveoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->