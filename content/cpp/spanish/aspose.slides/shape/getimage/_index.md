---
title: GetImage()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Devuelve la miniatura de la forma. Se utiliza por defecto el tipo de límites de miniatura ShapeThumbnailBounds::Shape."
type: docs
weight: 651
url: /es/aspose.slides/shape/getimage/
---
## Shape::GetImage() método

Devuelve la miniatura de la forma. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) el tipo de límites de miniatura de forma se usa por defecto.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### Valor devuelto

[Shape](../) miniatura.

## Shape::GetImage(ShapeThumbnailBounds, float, float) método

Devuelve la miniatura de la forma.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) tipo de límites de miniatura. |
| scaleX | **float** | escala X |
| scaleY | **float** | escala Y |

### Valor devuelto

[Shape](../) miniatura o null en caso de que [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) se use y una forma no tenga elementos visibles.

## Ver también

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImage](../../iimage/)
* Clase [Shape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)