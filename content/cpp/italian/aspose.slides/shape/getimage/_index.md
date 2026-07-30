---
title: GetImage()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce la miniatura della forma. Il tipo di limiti della miniatura della forma ShapeThumbnailBounds::Shape è usato per impostazione predefinita."
type: docs
weight: 651
url: /it/aspose.slides/shape/getimage/
---
## Shape::GetImage() metodo

Restituisce la miniatura della forma. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) il tipo di limiti della miniatura della forma è usato per impostazione predefinita.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### Valore di ritorno

[Shape](../) miniatura.

## Shape::GetImage(ShapeThumbnailBounds, float, float) metodo

Restituisce la miniatura della forma.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) tipo di limiti della miniatura. |
| scaleX | **float** | scala X |
| scaleY | **float** | scala Y |

### Valore di ritorno

[Shape](../) miniatura o null nel caso in cui [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) è usato e una forma non ha elementi visibili.

## Vedi anche

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../iimage/)
* Classe [Shape](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)