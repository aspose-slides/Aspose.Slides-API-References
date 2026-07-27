---
title: SetSize()
second_title: Referencia API de Aspose.Slides para C++
description: "Establece el tamaño de la diapositiva por tipo y escala el contenido existente. Asignar cualquier valor distinto de SlideSizeType::Custom ajusta el ISlideSize::get_Size según el tipo seleccionado, mientras se preserva ISlideSize::get_Orientation."
type: docs
weight: 53
url: /es/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) método

Establece el tamaño de la diapositiva por tipo y escala el contenido existente. Asignar cualquier valor distinto de [SlideSizeType::Custom](../../slidesizetype/) ajusta el [ISlideSize::get_Size](../get_size/) según el tipo seleccionado, mientras se preserva [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | El tamaño de diapositiva predefinido que se aplicará. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | El modo de escalado de contenido a usar. |
## Observaciones

Asignar cualquier valor distinto de [SlideSizeType::Custom](../../slidesizetype/) ajusta el [System::Drawing::Size](../../../system.drawing/size/) según el tipo seleccionado, mientras se preserva [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) método

Establece explícitamente las dimensiones de la diapositiva y escala el contenido existente. Esto restablece el valor [ISlideSize::get_Type](../get_type/) a [SlideSizeType::Custom](../../slidesizetype/) y establece el [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | **float** | El nuevo ancho de la diapositiva, en puntos. |
| height | **float** | La nueva altura de la diapositiva, en puntos. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | El modo de escalado de contenido a usar. |
## Observaciones

Esto restablece la propiedad [ISlideSize::get_Type](../get_type/) a [SlideSizeType::Custom](../../slidesizetype/) y establece el [Orientation](../../orientation/). 

## Ver también

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)