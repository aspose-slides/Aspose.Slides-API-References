---
title: RemoveAt
second_title: Referencia de API de Aspose.Slides para .NET
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 50
url: /es/aspose.slides/masterlayoutslidecollection/removeat/
---

## Método MasterLayoutSlideCollection.RemoveAt

Elimina el elemento en el índice especificado de la colección.

```csharp
public void RemoveAt(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero del elemento a eliminar. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Se lanza si el diseño se utiliza en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

1) Para evitar el lanzamiento de PptxEditException, verifica la propiedad HasDependingSlides del diseño antes. 2) También puedes usar el método [`Remove`](../../ilayoutslide/remove) para simplificar el código.

### Vea También

* clase [MasterLayoutSlideCollection](../../masterlayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../masterlayoutslidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->