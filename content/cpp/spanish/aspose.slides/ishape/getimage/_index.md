---
title: GetImage()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Devuelve la miniatura de la forma. ShapeThumbnailBounds::Shape tipo de límites de miniatura se utiliza por defecto."
type: docs
weight: 547
url: /es/aspose.slides/ishape/getimage/
---
## IShape::GetImage() método


Devuelve la miniatura de la forma. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) se utiliza el tipo de límites de miniatura de forma por defecto.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Valor de retorno

[Shape](../../shape/) miniatura.

## IShape::GetImage(ShapeThumbnailBounds, float, float) método


Devuelve la miniatura de la forma.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) tipo de límites de miniatura. |
| scaleX | **float** | escala X |
| scaleY | **float** | escala Y |

### Valor de retorno

[Shape](../../shape/) miniatura o null en caso de que [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) se use y una forma no tenga elementos visibles.

## Ver también

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImage](../../iimage/)
* Clase [IShape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)