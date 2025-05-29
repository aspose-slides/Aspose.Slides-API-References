---
title: Html5Options
second_title: Aspose.Slides para referencia de API .NET
description: Representa opciones de exportación HTML5.
type: docs
weight: 3690
url: /es/aspose.slides.export/html5options/
---

## Clase Html5Options

Representa opciones de exportación HTML5.

```csharp
public class Html5Options : SaveOptions, IHtml5Options
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Html5Options](html5options)() | Constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnimateShapes](../../aspose.slides.export/html5options/animateshapes) { get; set; } | Devuelve o establece la opción de animación de formas. Booleano de lectura/escritura. |
| [AnimateTransitions](../../aspose.slides.export/html5options/animatetransitions) { get; set; } | Devuelve o establece la opción de animación de transiciones. Booleano de lectura/escritura. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente original. Cadena de lectura/escritura. |
| [DisableFontLigatures](../../aspose.slides.export/html5options/disablefontligatures) { get; set; } | Obtiene o establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. De forma predeterminada, esta propiedad se establece en `false`. |
| [EmbedImages](../../aspose.slides.export/html5options/embedimages) { get; set; } | Devuelve o establece la opción de incrustar imágenes. Booleano de lectura/escritura. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [OutputPath](../../aspose.slides.export/html5options/outputpath) { get; set; } | Determina dónde deben almacenarse los recursos externos. Cadena de lectura/escritura. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de callback para guardar actualizaciones de progreso en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir los hipervínculos con llamadas a JavaScript al guardar la presentación. Booleano de lectura/escritura. El valor predeterminado es **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/html5options/slideslayoutoptions) { get; set; } | Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, new Html5Options()
  {
      AnimateShapes = true,
      AnimateTransitions = true
  });
}
```

### Ver También

* clase [SaveOptions](../saveoptions)
* interfaz [IHtml5Options](../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->