---
title: SetSize()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el tamaño de la diapositiva según el tipo y escala el contenido existente.
type: docs
weight: 53
url: /es/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) método

Establece el tamaño de la diapositiva según el tipo y escala el contenido existente.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | El tamaño de diapositiva predefinido a aplicar. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | El modo de escalado del contenido a usar. |

## Observaciones

Asignar cualquier valor distinto de [SlideSizeType::Custom](../../slidesizetype/) ajusta el [SlideSize::get_Size](../get_size/) según el tipo seleccionado, mientras conserva [SlideSize::get_Orientation](../get_orientation/).

## SlideSize::SetSize(float, float, SlideSizeScaleType) método

Establece explícitamente las dimensiones de la diapositiva y escala el contenido existente.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | **float** | El nuevo ancho de la diapositiva, en puntos. |
| height | **float** | El nuevo alto de la diapositiva, en puntos. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | El modo de escalado del contenido a usar. |

## Observaciones

Esto restablece la propiedad [SlideSize::get_Type](../get_type/) a [SlideSizeType::Custom](../../slidesizetype/) y establece el [Orientation](../../orientation/).

## Ver también

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Clase [SlideSize](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)