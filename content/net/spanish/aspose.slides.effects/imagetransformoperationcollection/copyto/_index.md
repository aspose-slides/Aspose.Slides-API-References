---
title: CopyTo
second_title: Referencia de API de Aspose.Slides para .NET
description: Copia los elementos de la ICollection a un Array comenzando en un índice particular del Array.
type: docs
weight: 240
url: /es/aspose.slides.effects/imagetransformoperationcollection/copyto/
---

## Método ImageTransformOperationCollection.CopyTo

Copia los elementos de la ICollection a un Array, comenzando en un índice particular del Array.

```csharp
public void CopyTo(IImageTransformOperation[] array, int arrayIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | IImageTransformOperation[] | El Array unidimensional que es el destino de los elementos copiados de ICollection. El Array debe tener indexación basada en cero. |
| arrayIndex | Int32 | El índice basado en cero en *array* donde comienza la copia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *array* es nulo. |
| ArgumentOutOfRangeException | *arrayIndex* es menor que 0. |
| ArgumentException | El número de elementos en la ICollection de origen es mayor que el espacio disponible desde *arrayIndex* hasta el final del *array* de destino. |

### Ver También

* interface [IImageTransformOperation](../../iimagetransformoperation)
* class [ImageTransformOperationCollection](../../imagetransformoperationcollection)
* namespace [Aspose.Slides.Effects](../../imagetransformoperationcollection)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->