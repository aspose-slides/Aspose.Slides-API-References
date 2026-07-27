---
title: AddBiLevelEffect()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega el nuevo efecto Bi-Level (blanco/negro) al final de una colección.
type: docs
weight: 144
url: /es/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) método

Agrega el nuevo efecto Bi-Level (blanco/negro) al final de una colección.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | **float** | el umbral de luminancia para el efecto Bi-Level. Los valores mayores o iguales al umbral se establecen a blanco. Los valores menores que el umbral se establecen a negro. |

### Valor devuelto

Índice del nuevo efecto de imagen en una colección.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IBiLevel](../../ibilevel/)
* Clase [ImageTransformOperationCollection](../)
* Espacio de nombres [Aspose::Slides::Effects](../../)
* Biblioteca [Aspose.Slides](../../../)