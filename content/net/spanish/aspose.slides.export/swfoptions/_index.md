---
title: SwfOptions
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.
type: docs
weight: 4550
url: /es/aspose.slides.export/swfoptions/
---
## SwfOptions clase

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
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Especifica si el documento SWF generado debe comprimirse o no. El valor predeterminado es `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que la fuente original no se encuentre. Lectura-escritura String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Habilita/deshabilita el menú contextual. El valor predeterminado es true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura-escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Especifica la calidad de las imágenes JPEG. El valor predeterminado es 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Imagen que se mostrará como logo en la esquina superior derecha del visor. La imagen debe ser PNG de 32x64 píxeles, de lo contrario el logo puede mostrarse incorrectamente. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Obtiene o establece la dirección completa del hipervínculo para un logo. Tiene efecto solo si se especifica un [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Mostrar/ocultar panel inferior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Mostrar/ocultar botón de pantalla completa. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Mostrar/ocultar panel izquierdo. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Mostrar/ocultar paginador de páginas. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Mostrar/ocultar sección de búsqueda. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Mostrar/ocultar todo el panel superior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lectura-escritura Boolean. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). Esta propiedad no admite la asignación de objetos del tipo [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Iniciar con el panel izquierdo abierto. Puede sobrescribirse en flashvars. El valor predeterminado es false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura-escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

El siguiente ejemplo muestra cómo convertir PowerPoint a Flash SWF.

```csharp
[C#]
// Instanciar un objeto Presentation que representa un archivo de presentación
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Guardar la presentación y las páginas de notas
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Ver también

* clase [SaveOptions](../saveoptions)
* interfaz [ISwfOptions](../iswfoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->