---
title: GetImage()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Shape-Miniatur zurück. ShapeThumbnailBounds::Shape shape thumbnail bounds type wird standardmäßig verwendet."
type: docs
weight: 651
url: /de/aspose.slides/shape/getimage/
---
## Shape::GetImage() Methode

Gibt die shape thumbnail zurück. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type wird standardmäßig verwendet.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### Rückgabewert

[Shape](../) Miniatur.

## Shape::GetImage(ShapeThumbnailBounds, float, float) Methode

Gibt die shape thumbnail zurück.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) Miniatur-Grenztyp. |
| scaleX | **float** | X-Skalierung |
| scaleY | **float** | Y-Skalierung |

### Rückgabewert

[Shape](../) Miniatur oder null, falls [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) verwendet wird und ein shape keine sichtbaren Elemente hat.

## Siehe auch

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)