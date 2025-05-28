---
title: InsertSummaryZoomFrame
second_title: Referencia de API de Aspose.Slides para .NET
description: Crea un nuevo objeto Summary Zoom y lo inserta en una colección en el índice especificado.
type: docs
weight: 380
url: /es/aspose.slides/shapecollection/insertsummaryzoomframe/
---

## Método ShapeCollection.InsertSummaryZoomFrame

Crea un nuevo objeto Summary Zoom y lo inserta en una colección en el índice especificado.

```csharp
public ISummaryZoomFrame InsertSummaryZoomFrame(int index, float x, float y, float width, 
    float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar el marco de Zoom de Sección. |
| x | Single | Coordenada X de un nuevo marco de Zoom de Sección. |
| y | Single | Coordenada Y de un nuevo marco de Zoom de Sección. |
| width | Single | Ancho de un nuevo marco de Zoom de Sección. |
| height | Single | Altura de un nuevo marco de Zoom de Sección. |

### Valor de Retorno

Objeto Summary Zoom creado [`ISummaryZoomFrame`](../../isummaryzoomframe).

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | No hay secciones en la presentación, o la diapositiva de destino no pertenece a ninguna sección. |

### Observaciones

Este método crea un nuevo Summary Zoom y coloca una colección de objetos en él para todas las secciones de esta presentación.

### Ejemplos

Este ejemplo demuestra la creación e inserción de un objeto Summary Zoom en el índice especificado de una colección (suponiendo que hay al menos dos secciones en la presentación "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISummaryZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSummaryZoomFrame(2, 150, 20, 50, 50);
}
```

### Véase También

* interfaz [ISummaryZoomFrame](../../isummaryzoomframe)
* clase [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->