---
title: FindShapesByPlaceholderType()
second_title: Referencia de API de Aspose.Slides para C++
description: Busca todas las formas en la diapositiva especificada que coinciden con el tipo de marcador de posición dado.
type: docs
weight: 14
url: /es/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) método

Busca todas las formas en la diapositiva especificada que coinciden con el tipo de marcador de posición dado.

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | La diapositiva en la que buscar formas. |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | El tipo de marcador de posición por el cual filtrar las formas. |

### Valor devuelto

Una matriz de objetos [IShape](../../../aspose.slides/ishape/) que coinciden con el tipo de marcador de posición especificado.

## Véase también

* Enumeración [PlaceholderType](../../../aspose.slides/placeholdertype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IShape](../../../aspose.slides/ishape/)
* Clase [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Clase [SlideUtil](../)
* Espacio de nombres [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)