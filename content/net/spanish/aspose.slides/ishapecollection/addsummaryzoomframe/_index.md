---
title: AddSummaryZoomFrame
second_title: Aspose.Slides para .NET Referencia de la API
description: Agrega un nuevo objeto de resumen de zoom al final de una colección.
type: docs
weight: 160
url: /es/aspose.slides/ishapecollection/addsummaryzoomframe/
---

## IShapeCollection.AddSummaryZoomFrame método

Agrega un nuevo objeto de resumen de zoom al final de una colección.

```csharp
public ISummaryZoomFrame AddSummaryZoomFrame(float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Single | Coordenada X de un nuevo marco de sección de zoom Single. |
| y | Single | Coordenada Y de un nuevo marco de sección de zoom Single. |
| width | Single | Ancho de un nuevo marco de sección de zoom Single. |
| height | Single | Altura de un nuevo marco de sección de zoom Single. |

### Valor de Retorno

Objeto de resumen de zoom creado [`ISummaryZoomFrame`](../../isummaryzoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | No hay secciones en la presentación, o la diapositiva objetivo no pertenece a ninguna sección. |

### Observaciones

Este método crea un nuevo resumen de zoom y coloca una colección de objetos dentro de él para todas las secciones en esta presentación.

### Ejemplos

Este ejemplo demuestra cómo agregar un objeto de resumen de zoom al final de una colección (suponiendo que hay al menos dos secciones en la presentación "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[0].Shapes.AddSummaryZoomFrame(150, 20, 500, 250);
}
```

### Véase También

* interfaz [ISummaryZoomFrame](../../isummaryzoomframe)
* interfaz [IShapeCollection](../../ishapecollection)
* espacio de nombres [Aspose.Slides](../../ishapecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->