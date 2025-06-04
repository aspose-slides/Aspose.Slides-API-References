---
title: IViewProperties
second_title: Referencia de API de Aspose.Slides para .NET
description: Propiedades de vista a nivel de presentación.
type: docs
weight: 7170
url: /es/aspose.slides/iviewproperties/
---

## Interfaz IViewProperties

Propiedades de vista a nivel de presentación.

```csharp
public interface IViewProperties
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [GridSpacing](../../aspose.slides/iviewproperties/gridspacing) { get; set; } | Devuelve o establece el espaciado de la cuadrícula que debe utilizarse para la cuadrícula subyacente al documento de presentación, en puntos. Lectura/escritura Single. |
| [LastView](../../aspose.slides/iviewproperties/lastview) { get; set; } | Especifica el modo de vista que se utilizó cuando se guardó por última vez el documento de presentación. Lectura/escritura [`ViewType`](../viewtype). |
| [NormalViewProperties](../../aspose.slides/iviewproperties/normalviewproperties) { get; } | Representa las propiedades de vista normal. La vista normal consta de tres regiones de contenido: la diapositiva en sí, una región de contenido lateral y una región de contenido inferior. Solo lectura [`INormalViewProperties`](../inormalviewproperties). |
| [NotesViewProperties](../../aspose.slides/iviewproperties/notesviewproperties) { get; } | Especifica las propiedades de vista comunes asociadas con el modo de vista de notas. Solo lectura [`ICommonSlideViewProperties`](../icommonslideviewproperties). |
| [ShowComments](../../aspose.slides/iviewproperties/showcomments) { get; set; } | Especifica si los comentarios de la diapositiva deben mostrarse. Lectura/escritura [`NullableBool`](../nullablebool). |
| [SlideViewProperties](../../aspose.slides/iviewproperties/slideviewproperties) { get; } | Especifica las propiedades de vista comunes asociadas con el modo de vista de diapositiva. Solo lectura [`ICommonSlideViewProperties`](../icommonslideviewproperties). |

### Ver también

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->