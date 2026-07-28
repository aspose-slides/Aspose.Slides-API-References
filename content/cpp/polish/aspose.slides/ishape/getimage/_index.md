---
title: GetImage()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Zwraca miniaturę kształtu. Typ granic miniatury kształtu ShapeThumbnailBounds::Shape jest używany domyślnie."
type: docs
weight: 547
url: /pl/aspose.slides/ishape/getimage/
---
## IShape::GetImage() metoda


Zwraca miniaturę kształtu. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) typ granic miniatury kształtu jest używany domyślnie.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```


### Wartość zwracana

[Shape](../../shape/) miniatura.

## IShape::GetImage(ShapeThumbnailBounds, float, float) metoda


Zwraca miniaturę kształtu.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Argumenty

| Parameter | Typ | Opis |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) typ granic miniatury. |
| scaleX | **float** | Skala X |
| scaleY | **float** | Skala Y |

### Wartość zwracana

[Shape](../../shape/) miniatura lub null w przypadku, gdy [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) jest używany i kształt nie ma widocznych elementów.

## Zobacz także

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IImage](../../iimage/)
* Klasa [IShape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)