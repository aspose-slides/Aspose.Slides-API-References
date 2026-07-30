---
title: GetImage()
second_title: Aspose.Slides per C++ API Reference
description: "Restituisce la miniatura della forma. Il tipo di limiti della miniatura ShapeThumbnailBounds::Shape è usato per impostazione predefinita."
type: docs
weight: 547
url: /it/aspose.slides/ishape/getimage/
---
## IShape::GetImage() metodo

Restituisce la miniatura della forma. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) il tipo di limiti della miniatura della forma è usato per impostazione predefinita.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### Valore di ritorno

[Shape](../../shape/) miniatura.

## IShape::GetImage(ShapeThumbnailBounds, float, float) metodo

Restituisce la miniatura della forma.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) tipo di limiti della miniatura. |
| scaleX | **float** | scala X |
| scaleY | **float** | scala Y |

### Valore di ritorno

[Shape](../../shape/) miniatura o null nel caso in cui [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) è usato e una forma non ha elementi visibili.

## Vedi anche

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)