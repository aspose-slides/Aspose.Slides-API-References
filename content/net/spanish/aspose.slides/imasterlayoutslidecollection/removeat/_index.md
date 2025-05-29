---
title: RemoveAt
second_title: Aspose.Slides para .NET Referencia de API
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 60
url: /es/aspose.slides/imasterlayoutslidecollection/removeat/
---

## IMasterLayoutSlideCollection.RemoveAt método

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
| [PptxEditException](../../pptxeditexception) | Lanzado si el diseño se usa en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

1) Para evitar lanzar el PptxEditException, verifica la propiedad HasDependingSlides del diseño antes. 2) También puedes usar el método [`Remove`](../../ilayoutslide/remove) para simplificar el código.

### Véase también

* interfaz [IMasterLayoutSlideCollection](../../imasterlayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../imasterlayoutslidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->