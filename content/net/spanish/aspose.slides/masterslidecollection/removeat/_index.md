---
title: RemoveAt
second_title: Referencia de API de Aspose.Slides para .NET
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 100
url: /es/aspose.slides/masterslidecollection/removeat/
---

## Método MasterSlideCollection.RemoveAt

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
| [PptxEditException](../../pptxeditexception) | Se lanza si el maestro a eliminar se utiliza en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

Para evitar que se lance la PptxEditException, verifica la propiedad HasDependingSlides del maestro primero.

### Véase también

* clase [MasterSlideCollection](../../masterslidecollection)
* espacio de nombres [Aspose.Slides](../../masterslidecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->