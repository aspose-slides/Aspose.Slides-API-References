---
title: RenderingOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Proporciona opciones que controlan cómo se renderiza una presentación/diapositiva.
type: docs
weight: 4220
url: /es/aspose.slides.export/renderingoptions/
---

## Clase RenderingOptions

Proporciona opciones que controlan cómo se renderiza una presentación/diapositiva.

```csharp
public class RenderingOptions : SaveOptions, IRenderingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RenderingOptions](renderingoptions)() | Constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Lectura/escritura String. |
| [DisableFontLigatures](../../aspose.slides.export/renderingoptions/disablefontligatures) { get; set; } | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en `true`, las ligaduras estarán desactivadas en la salida renderizada. Por defecto, esta propiedad se establece en `false`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/renderingoptions/inkoptions) { get; } | Proporciona opciones que controlan el aspecto de los objetos Ink en el documento exportado. Solo lectura [`IInkOptions`](../iinkoptions) |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de retorno de llamada para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura/escritura Booleano. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/renderingoptions/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
  {
  IRenderingOptions renderingOpts = new RenderingOptions();
  renderingOpts.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomTruncated };
  
  pres.Slides[0].GetThumbnail(renderingOpts).Save("pres-Original.png", ImageFormat.Png);
  
  renderingOpts.DefaultRegularFont = "Arial Black";
  pres.Slides[0].GetThumbnail(renderingOpts).Save("pres-ArialBlackDefault.png", ImageFormat.Png);
  
  renderingOpts.DefaultRegularFont = "Arial Narrow";
  pres.Slides[0].GetThumbnail(renderingOpts).Save("pres-ArialNarrowDefault.png", ImageFormat.Png);
}
```

### También te puede interesar

* clase [SaveOptions](../saveoptions)
* interfaz [IRenderingOptions](../irenderingoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->