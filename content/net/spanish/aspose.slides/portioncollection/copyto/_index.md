---
title: CopiarA
second_title: Aspose.Slides para referencia de API .NET
description: Copia los elementos del ICollection a un Array comenzando en un índice particular del Array.
type: docs
weight: 70
url: /es/aspose.slides/portioncollection/copyto/
---

## Método PortionCollection.CopyTo

Copia los elementos del ICollection a un Array, comenzando en un índice particular del Array.

```csharp
public void CopyTo(IPortion[] array, int arrayIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | IPortion[] | El Array unidimensional que es el destino de los elementos copiados del ICollection. El Array debe tener un índice basado en cero. |
| arrayIndex | Int32 | El índice basado en cero en *array* donde comienza la copia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *array* es nulo. |
| ArgumentOutOfRangeException | *arrayIndex* es menor que 0. |
| ArgumentException | El número de elementos en el ICollection fuente es mayor que el espacio disponible desde *arrayIndex* hasta el final del *array* de destino. |

### Ver también

* interfaz [IPortion](../../iportion)
* clase [PortionCollection](../../portioncollection)
* espacio de nombres [Aspose.Slides](../../portioncollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->