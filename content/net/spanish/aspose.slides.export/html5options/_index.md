---
title: Html5Options
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una opción de exportación de HTML5.
type: docs
weight: 3540
url: /es/aspose.slides.export/html5options/
---
## Html5Options class

Representa una opción de exportación de HTML5.

```csharp
public class Html5Options : SaveOptions, IHtml5Options
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Html5Options](html5options)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AnimateShapes](../../aspose.slides.export/html5options/animateshapes) { get; set; } | Devuelve o establece la opción de animación de formas. Lectura/escrituraBoolean . |
| [AnimateTransitions](../../aspose.slides.export/html5options/animatetransitions) { get; set; } | Devuelve o establece la opción de animación de transiciones. Lectura/escrituraBoolean . |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Lectura-escrituraString . |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Devuelve de establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se cancelará. Lectura/escritura[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

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

### Ver también

* class [SaveOptions](../saveoptions)
* interface [IHtml5Options](../ihtml5options)
* espacio de nombres [Aspose.Slides.Export](../../aspose.slides.export)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
