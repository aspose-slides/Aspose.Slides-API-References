---
title: RemoveAt
second_title: Aspose.Sildes para .NET Referencia de API
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 100
url: /es/aspose.slides/masterslidecollection/removeat/
---

## MasterSlideCollection.RemoveAt método

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
| [PptxEditException](../../pptxeditexception) | Se lanza si la master a eliminar está utilizada en la presentación (su propiedad HasDependingSlides es verdadera). |

### Comentarios

Para evitar que se lance la PptxEditException, verifica la propiedad HasDependingSlides de la master antes.

### Véase También

* clase [MasterSlideCollection](../../masterslidecollection)
* espacio de nombres [Aspose.Slides](../../masterslidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->