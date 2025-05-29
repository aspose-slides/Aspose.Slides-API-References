---
title: AddSummaryZoomSection
second_title: Aspose.Slides para .NET Referencia de API
description: Crea un nuevo objeto de Sección de Resumen con Zoom y lo añade a la colección
type: docs
weight: 50
url: /es/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---

## Método SummaryZoomSectionCollection.AddSummaryZoomSection

Crea un nuevo objeto de Sección de Resumen con Zoom y lo añade a la colección

```csharp
public ISummaryZoomSection AddSummaryZoomSection(ISection section)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | ISection | Sección para un nuevo elemento de Sección de Resumen con Zoom [`ISection`](../../isection) |

### Valor de Retorno

Elemento añadido [`ISummaryZoomFrame`](../../isummaryzoomframe)

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La sección referenciada no pertenece a la presentación actual o no contiene ninguna diapositiva. |

### Observaciones

Si ya existe un elemento para esta sección en la colección, se devuelve el elemento existente.

### Ejemplos

El ejemplo demuestra cómo obtener un elemento de Sección de Resumen con Zoom por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection newZoomSection = collection.AddSummaryZoomSection(pres.Sections[3]);
}
```

### Véase También

* interfaz [ISummaryZoomSection](../../isummaryzoomsection)
* interfaz [ISection](../../isection)
* clase [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)
* namespace [Aspose.Slides](../../summaryzoomsectioncollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->