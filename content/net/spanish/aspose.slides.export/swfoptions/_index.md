---
title: SwfOptions
second_title: Aspose.Sildes para .NET API Reference
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.
type: docs
weight: 4340
url: /es/aspose.slides.export/swfoptions/
---

## Clase SwfOptions

Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SwfOptions](swfoptions)() | Constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Especifica si el documento SWF generado debe estar comprimido o no. El valor predeterminado es `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Cadena de lectura y escritura. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Habilitar/deshabilitar el menú contextual. El valor predeterminado es true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Especifica la calidad de las imágenes JPEG. El valor predeterminado es 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Imagen que se mostrará como logotipo en la esquina superior derecha del visor. La imagen debe ser una imagen PNG de 32x64 píxeles, de lo contrario, el logotipo puede mostrarse incorrectamente. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Obtiene o establece la dirección completa del hipervínculo para un logotipo. Solo tiene efecto si se especifica una [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de callback para actualizaciones del progreso de guardado en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Mostrar/ocultar el panel inferior. Puede ser anulado en flashvars. El valor predeterminado es true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Mostrar/ocultar el botón de pantalla completa. Puede ser anulado en flashvars. El valor predeterminado es true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Mostrar/ocultar el panel izquierdo. Puede ser anulado en flashvars. El valor predeterminado es true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Mostrar/ocultar el paso de página. Puede ser anulado en flashvars. El valor predeterminado es true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Mostrar/ocultar la sección de búsqueda. Puede ser anulado en flashvars. El valor predeterminado es true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Mostrar/ocultar todo el panel superior. Puede ser anulado en flashvars. El valor predeterminado es true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Booleano de lectura y escritura. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). Esta propiedad no admite la asignación de objetos del tipo [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Iniciar con el panel izquierdo abierto. Puede ser anulado en flashvars. El valor predeterminado es false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

El siguiente ejemplo muestra cómo convertir PowerPoint a SWF Flash.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Guardar presentación y páginas de notas
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Ver También

* clase [SaveOptions](../saveoptions)
* interfaz [ISwfOptions](../iswfoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->