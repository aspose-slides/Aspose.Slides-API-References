---
title: GetImage()
second_title: Referência da API Aspose.Slides para C++
description: "Retorna a miniatura da forma. ShapeThumbnailBounds::Shape tipo de limites de miniatura de forma é usado por padrão."
type: docs
weight: 547
url: /pt/aspose.slides/ishape/getimage/
---
## IShape::GetImage() método


Retorna a miniatura da forma. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type é usado por padrão.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Valor de Retorno

[Shape](../../shape/) miniatura.

## IShape::GetImage(ShapeThumbnailBounds, float, float) método


Retorna a miniatura da forma.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) thumbnail bounds type. |
| scaleX | **float** | escala X |
| scaleY | **float** | escala Y |

### Valor de Retorno

[Shape](../../shape/) miniatura ou nulo no caso em que [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) é usado e uma forma não tem elementos visíveis.

## Ver também

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)