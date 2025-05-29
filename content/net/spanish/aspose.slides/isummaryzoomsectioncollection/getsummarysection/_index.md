---
title: GetSummarySection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve el elemento de la sección de zoom de resumen para la sección dada.
type: docs
weight: 40
url: /es/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---

## Método ISummaryZoomSectionCollection.GetSummarySection

Devuelve el elemento de la sección de zoom de resumen para la sección dada.

```csharp
public ISummaryZoomSection GetSummarySection(ISection section)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | ISection | Sección para encontrar [`ISection`](../../isection) |

### Valor de Retorno

[`ISummaryZoomSection`](../../isummaryzoomsection) o null si la colección no contiene un elemento para la sección.

### Ejemplos

El ejemplo demuestra cómo obtener el elemento de la sección de zoom de resumen por índice:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;
    ISummaryZoomSection selectedObject = collection.GetSummarySection(pres.Sections[2]);
}
```

### Véase También

* interfaz [ISummaryZoomSection](../../isummaryzoomsection)
* interfaz [ISection](../../isection)
* interfaz [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection)
* espacio de nombres [Aspose.Slides](../../isummaryzoomsectioncollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->