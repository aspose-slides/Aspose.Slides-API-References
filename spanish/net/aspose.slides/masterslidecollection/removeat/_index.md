---
title: RemoveAt
second_title: Referencia de la API de Aspose.Slides para .NET
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 100
url: /es/net/aspose.slides/masterslidecollection/removeat/
---
## MasterSlideCollection.RemoveAt method

Elimina el elemento en el índice especificado de la colección.

```csharp
public void RemoveAt(int index)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de base cero del elemento que se va a quitar. |

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Se lanza si el maestro que se va a eliminar se usa en la presentación (su propiedad HasDependingSlides es verdadera). |

### Observaciones

Para evitar el lanzamiento de la propiedad HasDependingSlides del maestro de verificación PptxEditException antes.

### Ver también

* class [MasterSlideCollection](../../masterslidecollection)
* espacio de nombres [Aspose.Slides](../../masterslidecollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->