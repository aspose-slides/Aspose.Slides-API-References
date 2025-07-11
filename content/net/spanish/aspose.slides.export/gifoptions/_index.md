---
title: GifOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa opciones de exportación de GIF.
type: docs
weight: 3650
url: /es/aspose.slides.export/gifoptions/
---

## Clase GifOptions

Representa opciones de exportación de GIF.

```csharp
public class GifOptions : SaveOptions, IGifOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifOptions](gifoptions)() | Inicializa una nueva instancia de la clase GifOptions. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultDelay](../../aspose.slides.export/gifoptions/defaultdelay) { get; set; } | Obtiene o establece el tiempo de retraso predeterminado [ms]. Este valor se utilizará si [`AdvanceAfterTime`](../../aspose.slides/islideshowtransition/advanceaftertime) no está establecido. El valor predeterminado es 1000. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Lectura-escritura String. |
| [ExportHiddenSlides](../../aspose.slides.export/gifoptions/exporthiddenslides) { get; set; } | Determina si las diapositivas ocultas serán exportadas. El valor predeterminado es falso. |
| [FrameSize](../../aspose.slides.export/gifoptions/framesize) { get; set; } | Obtiene o establece el tamaño del marco. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Devuelve o establece el estilo visual del degradado. Lectura/escritura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para actualizar el progreso de guardado en porcentaje. Ver [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Especifica si se deben omitir hipervínculos con llamadas a JavaScript al guardar la presentación. Lectura/escritura Boolean. El valor predeterminado es **falso**. |
| [TransitionFps](../../aspose.slides.export/gifoptions/transitionfps) { get; set; } | Obtiene o establece los FPS de transición [fotogramas/segundo]. El valor predeterminado es 25. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lectura/escritura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ejemplos

El siguiente ejemplo muestra cómo convertir presentaciones a GIF animados utilizando configuraciones personalizadas.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    pres.Save("pres.gif", SaveFormat.Gif, new GifOptions
    {
        FrameSize = new Size(960, 720), // el tamaño del GIF resultante
        DefaultDelay = 2000, // cuánto tiempo se mostrará cada diapositiva hasta que se cambie a la siguiente
        TransitionFps = 35 // aumentar los FPS para una mejor calidad de animación de transición
    });
}
```

### Ver También

* clase [SaveOptions](../saveoptions)
* interfaz [IGifOptions](../igifoptions)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->