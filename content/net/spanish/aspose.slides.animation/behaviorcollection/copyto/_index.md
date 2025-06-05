---
title: CopyTo
second_title: Aspose.Slides para .NET Referencia de API
description: Copia los elementos del ICollection a un Array comenzando en un índice particular del Array.
type: docs
weight: 70
url: /es/aspose.slides.animation/behaviorcollection/copyto/
---

## Método BehaviorCollection.CopyTo

Copia los elementos del ICollection a un Array, comenzando en un índice particular del Array.

```csharp
public void CopyTo(IBehavior[] array, int arrayIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | IBehavior[] | El Array unidimensional que es el destino de los elementos copiados de ICollection. El Array debe tener indexación basada en cero. |
| arrayIndex | Int32 | El índice basado en cero en *array* en el que comienza la copia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *array* es nulo. |
| ArgumentOutOfRangeException | *arrayIndex* es menor que 0. |
| ArgumentException | El número de elementos en el ICollection de origen es mayor que el espacio disponible desde *arrayIndex* hasta el final del *array* de destino. |

### Véase También

* interfaz [IBehavior](../../ibehavior)
* clase [BehaviorCollection](../../behaviorcollection)
* espacio de nombres [Aspose.Slides.Animation](../../behaviorcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->