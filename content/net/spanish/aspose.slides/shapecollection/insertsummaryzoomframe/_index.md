---
title: InsertSummaryZoomFrame
second_title: Aspose.Sildes para .NET Referencia de API
description: Crea un nuevo objeto de Resumen Zoom e inserta en una colección en el índice especificado.
type: docs
weight: 380
url: /es/aspose.slides/shapecollection/insertsummaryzoomframe/
---

## ShapeCollection.InsertSummaryZoomFrame método

Crea un nuevo objeto de Resumen Zoom e inserta en una colección en el índice especificado.

```csharp
public ISummaryZoomFrame InsertSummaryZoomFrame(int index, float x, float y, float width, 
    float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el marco de Sección Zoom. |
| x | Single | Coordenada X de un nuevo marco de Sección Zoom Single. |
| y | Single | Coordenada Y de un nuevo marco de Sección Zoom Single. |
| width | Single | Ancho de un nuevo marco de Sección Zoom Single. |
| height | Single | Altura de un nuevo marco de Sección Zoom Single. |

### Valor de Retorno

Objeto de Resumen Zoom creado [`ISummaryZoomFrame`](../../isummaryzoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | No hay secciones en la presentación, o la diapositiva objetivo no pertenece a ninguna sección. |

### Comentarios

Este método crea un nuevo Resumen Zoom y coloca una colección de objetos en él para todas las secciones en esta presentación.

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto de Resumen Zoom en el índice especificado de una colección (suponiendo que hay al menos dos secciones en la presentación "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSummaryZoomFrame(2, 150, 20, 50, 50);
}
```

### Ver También

* interfaz [ISummaryZoomFrame](../../isummaryzoomframe)
* clase [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->