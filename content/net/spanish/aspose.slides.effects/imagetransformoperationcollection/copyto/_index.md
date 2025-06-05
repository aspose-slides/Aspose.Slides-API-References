---
title: CopyTo
second_title: Aspose.Sildes para .NET Referencia de API
description: Copia los elementos de ICollection a un Array comenzando en un índice particular del Array.
type: docs
weight: 240
url: /es/aspose.slides.effects/imagetransformoperationcollection/copyto/
---

## ImageTransformOperationCollection.CopyTo método

Copia los elementos de ICollection a un Array, comenzando en un índice particular del Array.

```csharp
public void CopyTo(IImageTransformOperation[] array, int arrayIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | IImageTransformOperation[] | El Array unidimensional que es el destino de los elementos copiados de ICollection. El Array debe tener un índice basado en cero. |
| arrayIndex | Int32 | El índice basado en cero en *array* en el que comienza la copia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *array* es nulo. |
| ArgumentOutOfRangeException | *arrayIndex* es menor que 0. |
| ArgumentException | El número de elementos en la ICollection fuente es mayor que el espacio disponible desde *arrayIndex* hasta el final del *array* de destino. |

### Véase también

* interfaz [IImageTransformOperation](../../iimagetransformoperation)
* clase [ImageTransformOperationCollection](../../imagetransformoperationcollection)
* namespace [Aspose.Slides.Effects](../../imagetransformoperationcollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->