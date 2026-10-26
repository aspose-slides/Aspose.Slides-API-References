---
title: GetImage()
second_title: Aspose.Slides para C++ Referência da API
description: "Retorna a miniatura da forma. ShapeThumbnailBounds::Shape tipo de limites da miniatura da forma é usado por padrão."
type: docs
weight: 651
url: /pt/aspose.slides/shape/getimage/
---
## Shape::GetImage() método


Retorna a miniatura da forma. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) tipo de limites da miniatura da forma é usado por padrão.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Valor de Retorno

[Shape](../) miniatura.

## Shape::GetImage(ShapeThumbnailBounds, float, float) método


Retorna a miniatura da forma.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) tipo de limites da miniatura. |
| scaleX | **float** | escala X |
| scaleY | **float** | escala Y |

### Valor de Retorno

[Shape](../) miniatura ou nulo no caso em que [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) é usado e uma forma não possui elementos visíveis.

## Veja Também

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IImage](../../iimage/)
* classe [Shape](../)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)