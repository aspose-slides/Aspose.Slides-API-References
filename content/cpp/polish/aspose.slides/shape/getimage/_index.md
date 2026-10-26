---
title: GetImage()
second_title: Aspose.Slides dla C++ Referencja API
description: "Zwraca miniaturę kształtu. Domyślnie używany jest typ granic miniatury kształtu ShapeThumbnailBounds::Shape."
type: docs
weight: 651
url: /pl/aspose.slides/shape/getimage/
---
## Shape::GetImage() method

Zwraca miniaturę kształtu. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) domyślnie używany jest typ granic miniatury kształtu.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### Wartość zwracana

[Shape](../) miniatura.

## Shape::GetImage(ShapeThumbnailBounds, float, float) method

Zwraca miniaturę kształtu.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) typ granic miniatury. |
| scaleX | **float** | Skala X |
| scaleY | **float** | Skala Y |

### Wartość zwracana

[Shape](../) miniatura lub null w przypadku, gdy użyto [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) i kształt nie ma widocznych elementów.

## Zobacz również

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [Shape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)